# Task 3: Infrastructure as Code (IaC) with Terraform

## Objective

Provision a local Docker container using Terraform.

## Tools Used

- Terraform
- Docker
- Git Bash
- Nginx

## Project Description

This project demonstrates Infrastructure as Code (IaC) using Terraform to provision and manage a local Docker container.

Terraform is configured with the Docker provider to download the Nginx Docker image and create an Nginx container.

## Terraform Configuration

The project uses the following Terraform resources:

- Docker image: `nginx:latest`
- Docker container: `terraform-nginx`

## Port Mapping

The Nginx container runs on port `80`.

The host port `8081` is mapped to the container port `80`.

```text
localhost:8081 -> container:80
