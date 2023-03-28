# terraform-bitcoin-node

This will set up a Bitcoin Node on Google Cloud Platform using Terraform

## Getting Started

1. Update `variables.tf` and `credentials/accounts.json`
2. `terraform init` to initialize the directory
3. `terraform plan` to see planned actions
4. `terraform apply` to deploy bitcoin

## Access

```
gcloud compute ssh bitcoin-node --zone <zone> --project=<project_id>
```
