# AWS DevOps Pipeline Project

## Overview

This project demonstrates a production-ready DevOps environment using modern DevOps practices and AWS cloud infrastructure.

The application is a simple Flask web application deployed using Docker containers on AWS EC2 with a CI/CD pipeline powered by Jenkins and infrastructure provisioning using Terraform.

---

# Architecture

GitHub → Jenkins → Docker → AWS EC2 → CloudWatch

---

# Technologies Used

- AWS EC2 (Amazon Linux)
- Docker
- Jenkins
- Terraform
- Python Flask
- Git & GitHub
- AWS CloudWatch

---

# Project Structure

```bash
devops-project/
│
├── app/
│   ├── app.py
│   └── requirements.txt
│
├── terraform/
│   └── main.tf
│
├── Dockerfile
├── Jenkinsfile
└── README.md# 
