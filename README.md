# AWS EKS DevSecOps Platform

Production-style learning project: Terraform, Amazon EKS, GitHub Actions OIDC, ECR, Argo CD, Helm, observability and security.

## Roadmap
1. AWS account safety: identity, MFA, budget and cost alerts.
2. Terraform remote state, VPC, IAM and ECR.
3. EKS and application deployment.
4. CI security scanning and GitOps delivery.
5. Monitoring, incident labs and portfolio documentation.

## Application
Upstream workload: https://github.com/GoogleCloudPlatform/microservices-demo

## Cost warning
EKS control plane, NAT gateways, load balancers, compute and storage can incur charges even while idle. Provision only after confirming budget and teardown steps.
