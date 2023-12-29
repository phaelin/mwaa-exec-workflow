# Basic Local MWAA Workflow

This workflow is used to run commands against an ephemeral MWAA environment.

## Workflow Jobs
The workflow contains a `Execute Airflow Command`. It is triggered manually within GitHub Actions.

### Execute Job
This job calls a Custom GitHub Action called `MWAA Local Runner Action` in order to run airflow commands against a local (to the runner) MWAA environment.
