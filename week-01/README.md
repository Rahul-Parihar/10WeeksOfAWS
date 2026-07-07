# Week 1 Day 2 — IAM Challenge

## Name
Your Name

## Topics Practiced
- AWS account security
- Root MFA
- Billing alert
- IAM users
- IAM groups
- IAM roles and OIDC-based temporary access
- IAM policies
- JSON policy
- Least privilege
- Permission boundaries
- GitHub OIDC role for AWS access
- GitHub OIDC with AWS

## What I Learned
Today I learned how IAM controls access in AWS.

The most important concept I understood is:

> Identity + Permissions = Access

I also learned that root user should not be used for daily work and IAM roles can provide temporary access without long-lived access keys.

## Screenshots Added
- Root MFA
- Billing alert
- IAM user
- IAM group
- Policy attached
- S3 access test
- IAM role
- GitHub OIDC role
- GitHub Actions OIDC workflow success

## Custom Policy
Policy file added:

policies/custom-s3-readonly-policy.json

## Optional Advanced Challenge
I also completed GitHub OIDC with AWS and verified access using AWS STS temporary credentials.

Workflow file:

.github/workflows/aws-oidc-challenge.yml

Trust policy file:

oidc/trust-policy.json

## Key Takeaway
Least privilege means giving only the required permissions, nothing extra.
