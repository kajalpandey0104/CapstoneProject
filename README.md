# DevOps Accelerator: End-to-End Cloud-Native Project

A fully integrated DevOps project simulating real-world CI/CD workflows, infrastructure provisioning, monitoring, and automation — built for aspiring DevOps engineers.

---

## 📌 Project Overview

This DevOps Accelerator enables users to:

- Upload input files through a frontend hosted on S3 + CloudFront  
- Automatically trigger processing via Lambda and S3 events  
- Use pre-signed URLs for secure uploads  
- Deploy and manage infrastructure using Terraform  
- Automate pipelines via GitHub Actions  
- Monitor health and logs via CloudWatch  

---

## ⚙️ The Flow (How It Works)

1. User visits frontend site through browser  
2. Navigates through all sections  
3. Makes the payment and uploads screenshot / PDF file  
4. File is converted into pre-signed URL and stored in S3  
5. S3 event triggers AWS Lambda  
6. Lambda processes the file and logs in CloudWatch  
7. SNS sends alert after successful processing  

---

## 🚀 Tech Stack

| Layer | Tools & Services |
|------|----------------|
| Frontend | HTML/CSS + S3 + CloudFront |
| Backend | AWS Lambda (Python) |
| Infrastructure | Terraform |
| CI/CD | GitHub Actions |
| Monitoring | CloudWatch |
| Notification | SNS |
| Security | IAM Roles, Policies |

---

## 🔥 Key Features

### ✅ Infrastructure Auto-Provisioning
- Automated infrastructure setup using Terraform  
- Remote backend with S3 (state file) and DynamoDB (state locking)  

### ✅ CI/CD Automation
- Fully automated pipelines using GitHub Actions  
- Separate workflows for:
  - Frontend deployment  
  - Backend (Lambda) deployment  
  - Infrastructure provisioning  

### ✅ Cloud-Native Architecture
- Frontend hosted on S3 + CloudFront  
- Backend using AWS Lambda (serverless)  
- Cost-efficient and highly scalable  

### ✅ Secure File Upload
- Pre-signed S3 URLs for secure uploads  
- No direct exposure of S3 bucket  

### ✅ Monitoring & Alerts
- CloudWatch for logs and monitoring  
- SNS for email notifications  

### ✅ Modular & Scalable Design
- Easily extendable with new modules (like QA Bot, Project Generator)  
- Clean and organized folder structure  

---

## 📂 Project Structure
**frontend/
backend/
infra/terraform/
.github/workflows/
README.md******
---
****
git add .
git commit -m "Updated README"
git push

## 👨‍💻 Author
**Kajal Pandey**
