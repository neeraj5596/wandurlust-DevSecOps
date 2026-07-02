# 🚀 Wanderlust DevSecOps CI/CD Pipeline

> End-to-End DevSecOps CI/CD Pipeline for a MERN Stack Application using Jenkins, SonarQube, OWASP Dependency Check, Trivy, Docker, Docker Compose, MongoDB, Redis, and AWS EC2.

![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)
![Jenkins](https://img.shields.io/badge/Jenkins-CI-red?logo=jenkins)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue?logo=docker)
![SonarQube](https://img.shields.io/badge/SonarQube-Code%20Analysis-blue?logo=sonarqube)
![OWASP](https://img.shields.io/badge/OWASP-Dependency%20Check-orange)
![Trivy](https://img.shields.io/badge/Trivy-Vulnerability%20Scanner-brightgreen)
![AWS](https://img.shields.io/badge/AWS-EC2-orange?logo=amazonaws)

---

# 📌 Project Overview

This project demonstrates an **Enterprise-Level DevSecOps CI/CD Pipeline** for deploying the **Wanderlust MERN Stack Application** on AWS EC2.

The pipeline automates the complete software delivery lifecycle by integrating security scanning, code quality analysis, containerization, and deployment.

### Pipeline Features

- ✅ Source Code Checkout from GitHub
- ✅ Static Code Analysis using SonarQube
- ✅ Dependency Vulnerability Scan using OWASP Dependency Check
- ✅ SonarQube Quality Gate Validation
- ✅ File System Vulnerability Scan using Trivy
- ✅ Docker Image Build
- ✅ Docker Compose Deployment
- ✅ MongoDB & Redis Integration
- ✅ Deployment on AWS EC2

---

# ⚙️ Tech Stack

| Category | Technology |
|-----------|------------|
| Source Code Management | GitHub |
| CI/CD | Jenkins |
| Code Quality | SonarQube |
| Dependency Scanning | OWASP Dependency Check |
| Vulnerability Scanner | Trivy |
| Containerization | Docker |
| Orchestration | Docker Compose |
| Database | MongoDB |
| Cache | Redis |
| Cloud Platform | AWS EC2 |
| Backend | Node.js |
| Frontend | React (Vite) |

---

# 🔄 CI/CD Pipeline Workflow

```
GitHub
   │
   ▼
Clone Repository
   │
   ▼
SonarQube Analysis
   │
   ▼
OWASP Dependency Check
   │
   ▼
Quality Gate Validation
   │
   ▼
Trivy File System Scan
   │
   ▼
Docker Image Build
   │
   ▼
Docker Compose Deployment
   │
   ▼
Application Deployment
```

---

# 🌐 Running Application

The application is successfully deployed on **AWS EC2** using **Docker Compose**.

<p align="center">
<img src="Landing page.png" width="100%">
</p>

---

# 📷 Jenkins Pipeline

The Jenkins pipeline automates code analysis, security scanning, Docker image build, and deployment.

<p align="center">
<img src="pipeline.png" width="100%">
</p>

---

# 📊 SonarQube Dashboard

SonarQube performs:

- Static Code Analysis
- Bug Detection
- Code Smell Detection
- Security Vulnerability Detection
- Quality Gate Validation

<p align="center">
<img src="Sonar.png" width="100%">
</p>

---

# 🔒 DevSecOps Security Tools

## ✅ SonarQube

- Static Code Analysis
- Code Smells Detection
- Bug Detection
- Vulnerability Detection
- Security Hotspots
- Quality Gate Validation

---

## ✅ OWASP Dependency Check

- Dependency Vulnerability Scanning
- CVE Detection
- HTML & XML Report Generation
- Third-Party Library Security Analysis

---

## ✅ Trivy

- File System Vulnerability Scan
- Secret Detection
- Misconfiguration Detection
- OS Package Vulnerability Scan

---

# 🐳 Docker Deployment

Docker Compose deploys the complete MERN application.

### Containers

- Frontend
- Backend
- MongoDB
- Redis

Deploy the application using:

```bash
docker compose up -d --build
```

Check running containers:

```bash
docker ps
```

---

# ☁️ AWS Deployment

The application is deployed on an AWS EC2 instance.

### Services Running

- Jenkins
- SonarQube
- Docker
- Docker Compose
- MongoDB
- Redis

---

# 📂 Repository Structure

```
.
├── backend/
├── frontend/
├── docker-compose.yml
├── Jenkinsfile
├── README.md
├── Landing page.png
├── pipeline.png
└── Sonar.png
```

---

# 🚀 Future Enhancements

- Kubernetes Deployment
- Helm Charts
- Prometheus Monitoring
- Grafana Dashboard
- ArgoCD GitOps
- Email Notifications
- Kubernetes Security Scanning

---

# 👨‍💻 Author

## Neeraj Kumar Verma

**Linux | DevOps | Cloud Engineer**

