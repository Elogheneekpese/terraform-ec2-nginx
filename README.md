# Terraform EC2 + Nginx Setup

This project uses Terraform to create a virtual machine (EC2 instance) in AWS and install Nginx, a web server.

## What it does:

- Sets up a VPC and subnet
- Creates a security group that allows SSH (port 22) and HTTP (port 80)
- Launches an EC2 instance with Amazon Linux
- Lets you connect and start Nginx

## How to deploy:

```bash
terraform init
terraform apply
