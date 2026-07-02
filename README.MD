# 🚀 Wanderlust DevSecOps CI/CD Pipeline

> End-to-End DevSecOps Pipeline for a MERN Stack Application using Jenkins, Docker, SonarQube, OWASP Dependency Check, Trivy, MongoDB, Redis and AWS EC2.

---

# 📌 Project Overview

This project demonstrates an enterprise-grade DevSecOps CI/CD pipeline for deploying the Wanderlust MERN application.

The application is automatically built, analyzed, scanned for vulnerabilities and deployed using Docker Compose.

---

# 🏗 Architecture

<img src="images/architecture.png">

---

# ⚙️ Tech Stack

| Category | Tools |
|----------|--------|
| SCM | GitHub |
| CI | Jenkins |
| Code Quality | SonarQube |
| Dependency Scan | OWASP Dependency Check |
| Security Scan | Trivy |
| Containers | Docker |
| Orchestration | Docker Compose |
| Database | MongoDB |
| Cache | Redis |
| Cloud | AWS EC2 |
| Backend | Node.js |
| Frontend | React (Vite) |

---

# 🔄 CI/CD Pipeline

The Jenkins Pipeline performs the following stages:

✅ Clone Source Code

↓

✅ SonarQube Static Code Analysis

↓

✅ OWASP Dependency Check

↓

✅ Sonar Quality Gate Validation

↓

✅ Trivy Filesystem Scan

↓

✅ Docker Image Build

↓

✅ Docker Compose Deployment

↓

✅ Application Deployment

---

# 🔒 Security Scanning

## SonarQube

- Static Code Analysis
- Code Smells Detection
- Bugs Detection
- Vulnerabilities
- Quality Gate Validation

📷 Screenshot

![Sonar](images/sonarqube.png)

---

## OWASP Dependency Check

- Detect Vulnerable Libraries
- CVE Scanning
- Dependency Report Generation

📷 Screenshot

![OWASP](images/dependency-check.png)

---

## Trivy

Filesystem Scan

- OS Packages
- Vulnerabilities
- Secrets
- Misconfigurations

📷 Screenshot

![Trivy](images/trivy.png)

---

# 🐳 Docker Deployment

Application deployed using Docker Compose.

Containers

- Frontend
- Backend
- MongoDB
- Redis

```bash
docker compose up -d --build
```

---

# ☁ AWS Deployment

Application hosted on AWS EC2 Instance.

Services Running

- Jenkins
- SonarQube
- MongoDB
- Redis
- Docker
- Docker Compose

---

# 📸 Project Screenshots

## Jenkins Pipeline

![Pipeline](images/pipeline.png)

---

## SonarQube Dashboard

![Sonar](images/sonarqube-dashboard.png)

---

## Dependency Check Report

![Dependency](images/dependency-report.png)

---

## Trivy Report

![Trivy](images/trivy-report.png)

---

## Docker Containers

![Docker](images/docker.png)

---

## Running Application

![Application](images/application.png)

---

# 📂 Repository Structure

```
.
├── backend
├── frontend
├── Jenkinsfile
├── docker-compose.yml
├── README.md
└── images
```

---

# 🚀 Pipeline Workflow

```text
GitHub
   │
   ▼
Jenkins
   │
   ▼
SonarQube
   │
   ▼
OWASP Dependency Check
   │
   ▼
Quality Gate
   │
   ▼
Trivy Scan
   │
   ▼
Docker Build
   │
   ▼
Docker Compose
   │
   ▼
AWS EC2 Deployment
```

---

# 📈 Future Improvements

- Kubernetes Deployment
- Helm Charts
- Prometheus Monitoring
- Grafana Dashboard
- ArgoCD
- Kubernetes Security Scanning
- Email Notifications

---

# 👨‍💻 Author

**Neeraj Kumar Verma**

Linux | DevOps | Cloud Engineer

LinkedIn:
https://linkedin.com/in/your-link

GitHub:
https://github.com/neeraj5596

Portfolio:
https://www.neerajverma.space

---

⭐ If you found this project helpful, don't forget to star the repository.
