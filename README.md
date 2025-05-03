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

<pre> ### 📁 Project Structure ```text terraform-aws-vpc/ ├── provider.tf # AWS provider setup ├── main.tf # VPC and core resources ├── variables.tf # Input variables ├── outputs.tf # Exported outputs └── README.md # This file ``` </pre>


---

## 🛠️ Usage

### 🔧 Prerequisites

- AWS CLI configured (`aws configure`)
- Terraform installed (`terraform -v`)
- AWS IAM user with permissions to create network resources

### 🧪 How to Run

```bash
terraform init
terraform plan
terraform apply
