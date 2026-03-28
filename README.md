
<p align="center">
<img src="Deploylynx%20Log.gif" width="220">
</p>


# 🚀 DeployLynx DevSecOps CI/CD Pipeline

<p align="center">
<img src="deploylynx-logo.gif" width="220">
</p>

<p align="center">
<b>Production-Style DevSecOps CI/CD Pipeline</b><br>
Containerized application with automated security scanning
</p>

---

# 📊 CI/CD Pipeline Status

![CI](https://img.shields.io/badge/CI-GitHub_Actions-blue?logo=githubactions)
![Docker](https://img.shields.io/badge/Container-Docker-blue?logo=docker)
![Security](https://img.shields.io/badge/Security-Trivy-green?logo=linux)
![Language](https://img.shields.io/badge/App-Python-yellow?logo=python)

---

# 📌 Project Overview

This project demonstrates a **DevSecOps CI/CD pipeline** used in modern cloud engineering environments.

The pipeline automatically:

• Builds container images
• Performs vulnerability scanning
• Validates code on every push
• Ensures secure application delivery

This architecture simulates **real enterprise DevOps workflows**.

---

# 🏗️ DevSecOps Architecture

```
Developer
   │
   │ Push Code
   ▼
GitHub Repository
   │
   │ triggers
   ▼
GitHub Actions CI/CD Pipeline
   │
   ├── Checkout Code
   │
   ├── Docker Build
   │
   ├── Security Scan (Trivy)
   │
   ▼
Secure Container Application
```

---

# ⚙️ Tech Stack

<details>
<summary>Click to view technologies</summary>

### CI/CD

GitHub Actions

### Containerization

Docker

### Security Scanning

Trivy

### Application Framework

Python Flask

### Version Control

Git + GitHub

</details>

---

# 🔁 CI/CD Workflow

1️⃣ Developer pushes code to repository

2️⃣ GitHub Actions pipeline starts automatically

3️⃣ Docker builds the container image

4️⃣ Trivy scans for vulnerabilities

5️⃣ Pipeline reports results

---

# 📂 Project Structure

```
deploylynx-devsecops-pipeline
│
├── app
│   └── app.py
│
├── Dockerfile
│
├── requirements.txt
│
└── .github
    └── workflows
        └── pipeline.yml
```

---

# 🐳 Docker Container

The application runs inside a **Docker container**, ensuring:

• consistent runtime environment
• easy deployment
• scalable infrastructure

---

# 🔐 Security Scanning

The pipeline integrates **Trivy vulnerability scanning** to detect:

• dependency vulnerabilities
• OS package risks
• configuration weaknesses

This follows **DevSecOps best practices**.

---

# 📈 CI/CD Automation

Every push automatically triggers:

GitHub Actions workflow which performs:

✔ Code checkout
✔ Docker build
✔ Security scanning

---

# 💡 Skills Demonstrated

This project highlights key DevOps engineering capabilities:

• CI/CD automation
• containerized applications
• DevSecOps security integration
• cloud-ready infrastructure practices

---

# 🏢 Organization

Developed by **DeployLynx Engineering**

```
Cloud • DevOps • Automation • Security
```

---

# ⭐ DeployLynx Mission

Building **secure, scalable and automated cloud infrastructure** through modern DevOps engineering practices.
