# 🚀 Terraform AWS EC2 Deployment

This project demonstrates how to provision a **Linux EC2 instance on AWS** using **Terraform**.  
It showcases the use of Infrastructure as Code (IaC) to deploy cloud resources in an automated, repeatable, and consistent manner.

---

## 🧰 Tools & Technologies Used

| Tool/Tech | Purpose |
|-----------|----------|
| Terraform | Infrastructure as Code |
| AWS EC2   | Virtual Machine (Linux Server) |
| AWS IAM   | Permissions & access for Terraform |
| Git & GitHub | Version control |
| Windows / Ubuntu Terminal | Execution environment |

---

## 📍 Project Overview

This Terraform configuration creates a **Linux EC2 instance** on AWS with the required networking and security configuration.  
It eliminates the need to manually create EC2 servers from the AWS console.

### ✅ What This Project Does

- Deploys a Linux EC2 instance (Amazon Linux / Ubuntu)  
- Creates a Security Group for secure access  
- Generates or uses a key pair for SSH login  
- Automates the entire provisioning using Terraform commands  

---

## 📂 Project Structure

.
├── main.tf # Main Terraform configuration (EC2 + Security Group)
├── .terraform.lock.hcl # Provider dependency lock file
└── README.md # Project documentation