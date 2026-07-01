# AWS S3 Bucket Provisioning with Terraform

This project demonstrates the use of **Infrastructure as Code (IaC)** to automate the creation and management of AWS S3 buckets using **Terraform**.

## 🚀 Project Overview
Instead of manually creating resources in the AWS Management Console, this project uses Terraform to define infrastructure in a declarative way. This ensures that the environment is reproducible, version-controlled, and easy to maintain.

## 🛠 Technologies Used
* **Terraform**: For provisioning and managing AWS infrastructure.
* **AWS S3**: Scalable cloud storage.
* **AWS CLI**: For managing authentication and credentials.

## 📂 Project Structure
```text
├── .terraform/          # (Ignored) Local provider plugins
├── .gitignore           # Keeps sensitive files (state, .tfvars) out of Git
├── main.tf              # The core blueprint defining the S3 bucket
├── terraform.tfstate    # (Ignored) Tracks the state of the infrastructure
└── README.md            # Project documentation