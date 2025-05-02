# 🌐 Terraform AWS VPC

This project creates a customizable Virtual Private Cloud (VPC) on AWS using **Terraform**. It's a great starting point for building production-grade infrastructure with **Infrastructure as Code (IaC)**.

---

## 🚀 Features

- Custom VPC with CIDR block
- Public and private subnets (extendable)
- Internet Gateway
- Route Table
- Outputs for integration with other modules

---

## 📁 Project Structure

<pre> terraform-aws-vpc/ ├── <b>provider.tf</b> # AWS provider setup ├── <b>main.tf</b> # VPC and core resources ├── <b>variables.tf</b> # Input variables ├── <b>outputs.tf</b> # Exported outputs └── <b>README.md</b> # This file </pre>
