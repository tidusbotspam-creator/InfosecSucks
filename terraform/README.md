# Terraform Azure Example

This project demonstrates a basic Terraform setup for deploying resources to Microsoft Azure.

## Structure
- `main.tf`: Main resources (example: Azure Resource Group)
- `variables.tf`: Input variables
- `outputs.tf`: Output values
- `provider.tf`: Provider configuration

## Usage
1. Install [Terraform](https://www.terraform.io/downloads.html)
2. Authenticate with Azure CLI: `az login`
3. Initialize Terraform:
   ```sh
   terraform init
   ```
4. Plan the deployment:
   ```sh
   terraform plan
   ```
5. Apply the deployment:
   ```sh
   terraform apply
   ```
