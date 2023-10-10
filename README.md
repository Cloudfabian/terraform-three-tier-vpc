# Terraform Three Tier Network VPC 

## Overview

This Terraform project sets up a Three Tier Network VPC on AWS. The architecture includes a Virtual Private Cloud (VPC) with three tiers: public, private, and database. Each tier is designed with specific access controls and configurations.

## Project Structure

- `main.tf`: Defines AWS resources such as VPC, subnets, internet gateway, and route tables.
- `variables.tf`: Contains variables used in the Terraform configuration (e.g., VPC CIDR blocks, availability zones).
- `terraform.tfstate`: Maintains the current state of resources.
- `outputs.tf`: Specifies the outputs that will be displayed after applying the configuration.

## Prerequisites

Before using this project, ensure you have the following installed:

- [Terraform](https://www.terraform.io/downloads.html)
- [AWS CLI](https://aws.amazon.com/cli/)

# Acknowledgements

- Thanks to [AWS](www.aws.amazon.com) for providing the cloud infrastructure.
- [Terraform](www.terraform.io) for making infrastructure as code possible.
- This project is based on the tutorial by [Samuel Nnanna](https://medium.com/@samuelnnanna71/an-entry-level-project-using-terraform-to-create-a-three-tier-network-vpc-8a67b81c145f) on [Medium](www.medium.com). Thank you for providing the inspiration and initial codebase for this project.
