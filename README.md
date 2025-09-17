# project-bedrock
InnovateMart’s Inaugural EKS Deployment

**Project Bedrock** is the infrastructure repository for deploying InnovateMart's `retail-store-sample-app` to Amazon EKS using Terraform and GitHub Actions.

## What is inside
- `infra/terraform/` — Terraform code (VPC, EKS, IAM scaffolding)
- `k8s/` — Kubernetes manifests for in-cluster databases and microservices
- `.github/workflows/terraform.yml` — CI pipeline to run `terraform plan` (feature/*) and `terraform apply` (main)
- `docs/deployment-guide.md` — quick runbook and architecture notes

