🔐 Naming Convention for Secrets in GitHub Workflows
AWS Accounts

All AWS-related secrets follow the naming pattern:
the5ers-<account>

Example: the5ers-staging

The GitHub OIDC role for each AWS account is stored under its corresponding secret group.

For instance, the OIDC role for the staging account is stored in the5ers-staging, and likewise for other environments.

GCP Accounts

All GCP-related secrets follow the naming pattern:
ttp-<project>

Example: ttp-staging

Each GCP project's secrets are scoped under its respective namespace to maintain clear separation between environments.
