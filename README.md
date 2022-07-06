# actions-debug-schedule-and-reusable-workflows
Minimal examples for evaluation and bugreport.

## .github/workflows/simple-scheduled.yml

- simple independent workflow running on a schedule

## .github/workflows/called-workflow.yml

- workflow that can be called by other workflows

## .github/workflows/caller-simple.yml

- workflow that calls called-workflow.yml on push and workflow_dispatch events

## .github/workflows/caller-scheduled.yml

- workflow that calls called-workflow.yml on schedule
- __NOT OPERATIONAL__
