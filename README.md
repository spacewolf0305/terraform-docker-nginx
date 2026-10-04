# Terraform + Docker Nginx Deployment

A beginner hands-on project to learn Infrastructure as Code using
Terraform with Docker.

## What I practiced

- Terraform Docker provider
- Docker images
- Docker containers
- Port mapping
- terraform init
- terraform plan
- terraform apply
- terraform destroy
- Managing infrastructure changes with Terraform

## Architecture

Terraform
   ↓
Docker
   ↓
Nginx Container
   ↓
localhost:9090

## Deployment

Terraform creates an Nginx Docker image and container.

The container's port 80 is mapped to port 9090 on the host.

Open:

http://localhost:9090

## Cleanup

terraform destroy
