# Prerequisites

- Ubuntu workstation with Git, Docker, Terraform, AWS CLI v2, kubectl and Helm.
- GitHub account with SSH authentication.
- AWS account with MFA and an identity with appropriately scoped permissions.
- AWS Budget and billing alerts configured before provisioning.

## Safe read-only checks
```bash
aws --version
aws sts get-caller-identity
aws configure list
```
Do not share access keys, tokens or credentials. Review output before sharing.
