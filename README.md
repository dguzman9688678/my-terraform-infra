# My Terraform Infra (Private Repo)

This repository contains **private Terraform code** for provisioning infrastructure on Google Cloud Platform (GCP).  
**Access is restricted; this repo is for personal use only.**

## Overview

- **Purpose:** Personal automation of GCP infrastructure using Terraform.
- **Cloud Provider:** Google Cloud Platform (GCP)
- **Tech:** Terraform

## Structure

- `main.tf` – Main configuration.
- `variables.tf` – Input variables.
- `outputs.tf` – Output values.
- `.terraform/` – (ignored) Terraform modules/cache.
- `.gitignore` – Ensures sensitive or generated files are not tracked.

## Usage

1. **Install Terraform:**  
   [Download Terraform](https://www.terraform.io/downloads.html)

2. **Clone this repo:**  
   *(Requires access to your private repo)*
   ```sh
   git clone https://github.com/dguzman9688678/my-terraform-infra.git
   cd my-terraform-infra
   ```

3. **Initialize Terraform:**  
   ```sh
   terraform init
   ```

4. **Review/Edit Variables:**  
   - Update `variables.tf` or use `terraform.tfvars` for your settings.

5. **Apply Infrastructure:**  
   ```sh
   terraform apply
   ```

## Notes

- **This repo is private. Do not share or publish.**
- Keep secrets and sensitive files out of git.
- Use `.gitignore` to avoid tracking generated and secret files.

## Requirements

- Terraform >= 1.3
- GCP credentials with necessary permissions

## Useful Links

- [Terraform Documentation](https://www.terraform.io/docs)
- [GCP Terraform Modules](https://registry.terraform.io/browse/providers/hashicorp/google)
