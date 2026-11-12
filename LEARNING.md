# Learning log

## Phase 0
- Built: AWS access checked (S3, Glue, Athena, Lambda, Step Functions, EventBridge, Logs), repo, venv, dataset
- Broke: IAM user console password and S3 bucket creation in us-east-1 were denied
- Why: organization policies (a region lock and an IAM restriction)
- Would change: check the region and account type before planning
- Still don't understand: how service control policies work

### Predictions (write BEFORE running)
- orders rows: ___
- order_items rows: ___
- reviews rows: ___