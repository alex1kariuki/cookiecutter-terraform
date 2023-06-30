# {{cookiecutter.project_name}}

{{cookiecutter.project_short_description}}

Version: {{cookiecutter.version}}

This repository contains the Terraform modules for deploying and managing the infrastructure of {{cookiecutter.project_name}}.

## Requirements

- Terraform >= 0.12.x
- A suitable cloud provider account (AWS, Google Cloud, etc.)

## Usage

Clone the repository:

```bash
git clone https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_slug}}.git

Navigate to the desired environment:

```bash
cd {{cookiecutter.project_slug}}/env/dev # or "prod" for production

Initialize Terraform:

```bash
terraform init

Plan and apply your changes:

```bash
terraform plan
terraform apply

## Modules (Roadmap item)

## Maintainer

Github: @alex1kariuki[https://github.com/alex1kariuki]
