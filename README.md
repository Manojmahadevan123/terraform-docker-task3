# Task 3: Infrastructure as Code with Terraform

## Objective
Provision a Docker container using Terraform.

## Tools Used
- Terraform
- Docker
- Amazon Linux 2023
- Nginx

## Implementation
1. Installed Terraform and Docker on EC2.
2. Configured the Docker provider.
3. Created an Nginx Docker image using Terraform.
4. Provisioned and started the Docker container.
5. Verified using docker ps and terraform state list.

## Commands
- terraform init
- terraform fmt
- terraform validate
- terraform plan
- terraform apply
- terraform state list
- terraform destroy

## Result
Successfully provisioned an Nginx container using Terraform.
The container was mapped to local port 8081.
