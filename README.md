# Terraform EC2 Project

This project creates an AWS EC2 instance using Terraform.

## Project Files

- `terraform.tf` - Terraform configuration
- `provider.tf` - AWS provider
- `variables.tf` - Input variables
- `terraform.tfvars` - Variable values
- `ec2.tf` - EC2, Security Group, Key Pair
- `outputs.tf` - Outputs
- `my-key.pub` - Public SSH key

## Prerequisites

- Terraform
- AWS CLI
- AWS Account
- SSH Key Pair

## Commands

Initialize Terraform

```bash
terraform init
```

Preview changes

```bash
terraform plan
```

Create resources

```bash
terraform apply
```

Delete resources

```bash
terraform destroy
```

## Resources Created

- EC2 Instance
- Security Group
- Key Pair

