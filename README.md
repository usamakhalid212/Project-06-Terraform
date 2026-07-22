🚀 Project 06 – Infrastructure as Code with Terraform on AWS

📌 Overview

This project demonstrates Infrastructure as Code (IaC) using Terraform to provision AWS infrastructure and deploy a Dockerized portfolio application on Amazon EC2.

Instead of manually creating cloud resources, Terraform automates the provisioning of infrastructure, making deployments repeatable, version-controlled, and consistent.

---

🏗️ Architecture

```
Terraform
      │
      ▼
AWS Provider
      │
      ▼
Security Group
      │
      ▼
EC2 Instance
      │
      ▼
Docker Engine
      │
      ▼
Docker Compose
      │
      ▼
Nginx Container
      │
      ▼
Portfolio Website
```

---

⚙️ Technologies Used

- Terraform
- AWS EC2
- AWS Security Groups
- Ubuntu 24.04 LTS
- Docker
- Docker Compose
- Nginx
- Git
- GitHub

---

📂 Project Structure

```
Project-06-Terraform
│
├── provider.tf
├── variables.tf
├── terraform.tfvars
├── main.tf
├── outputs.tf
├── .gitignore
├── screenshots/
└── README.md
```

---

🚀 Features

- Infrastructure provisioning using Terraform
- Automated EC2 instance creation
- Automated Security Group configuration
- Dockerized portfolio deployment
- Containerized Nginx web server
- Infrastructure version controlled with Git
- Infrastructure removal using Terraform Destroy

---

🚀 Deployment

Initialize Terraform

```bash
terraform init
```

Validate configuration

```bash
terraform validate
```

Review execution plan

```bash
terraform plan
```

Provision infrastructure

```bash
terraform apply
```

Destroy infrastructure

```bash
terraform destroy
```
---

👨‍💻 Author

**Usama Khalid**

GitHub:
https://github.com/usamakhalid212

LinkedIn:
https://www.linkedin.com/in/usama-khalid-0034532b2/
