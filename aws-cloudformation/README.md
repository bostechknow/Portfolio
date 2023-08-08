# AWS Cloudformation

A collection of Cloudformation templates that have been used/deployed in a production environment.

- `Demo-secrets.yaml` - Deploys secrets in a master account to be shared to all accounts in the Organization.
- `ec2-cleanup-lambda.yaml` - Deploys a lambda to daily check for instances/ebs volumes over a defined age for automated termination.
