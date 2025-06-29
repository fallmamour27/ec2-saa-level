# EC2 Solutions Architect Associate Terraform Project

This Terraform project deploys an AWS EC2 instance with a security group and an Elastic IP.  
It is designed as a learning project aligned with the AWS Solutions Architect Associate certification topics.

## Features

- AWS EC2 instance with customizable AMI and instance type  
- Security group allowing HTTP (port 80) and SSH (port 22) access  
- Elastic IP associated with the EC2 instance  

## Usage

1. Configure variables in your Terraform files or via CLI/environment variables.  
2. Run `terraform init` to initialize the project.  
3. Run `terraform plan` to preview the infrastructure changes.  
4. Run `terraform apply` to deploy the infrastructure.

## Prerequisites

- AWS CLI configured with appropriate credentials  
- Terraform installed (version 1.0+ recommended)  

## Notes

- Customize the AMI ID and instance type as needed.  
- Ensure your SSH key pair exists in the target AWS region.

