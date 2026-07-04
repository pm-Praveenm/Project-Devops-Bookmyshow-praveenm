# 🚀 Book My Show App Deployment using DevSecOps

Welcome to the **Book My Show App Deployment** project! This project demonstrates how to deploy a **Book My Show Clone** application using modern **DevOps** and **DevSecOps** practices, ensuring automation, scalability, monitoring, and security throughout the deployment pipeline.

---

## 📌 Project Overview

This project showcases an end-to-end DevSecOps workflow, including:

- 📂 Source Code Management with GitHub
- ⚙️ Continuous Integration & Continuous Deployment using Jenkins
- 🔍 Code Quality Analysis with SonarQube
- 🐳 Application Containerization using Docker
- ☸️ Kubernetes Deployment on Amazon EKS
- 📊 Monitoring with Prometheus & Grafana
- 🔒 Security Scanning using Trivy and OWASP Best Practices

---

## 🛠️ Tech Stack

| Category | Tool |
|----------|------|
| 📁 Version Control | GitHub |
| 🔄 CI/CD | Jenkins |
| 🔍 Code Quality | SonarQube |
| 🐳 Containerization | Docker |
| ☸️ Container Orchestration | Kubernetes (Amazon EKS) |
| 📊 Monitoring | Prometheus & Grafana |
| 🔒 Security | Trivy & OWASP |

---

# 🚦 Project Workflow

## 📦 Phase 1: Docker Deployment

In this phase, the application is containerized and executed using Docker.

### Steps

- Create a Dockerfile for the application
- Build the Docker image
- Push the image to a container registry
- Pull and run the container
- Verify application accessibility

---

## ☸️ Phase 2: Kubernetes Deployment (Amazon EKS)

Deploy the containerized application to an **Amazon Elastic Kubernetes Service (EKS)** cluster.

### Steps

- Create an Amazon EKS cluster
- Configure Kubernetes manifests
- Deploy the application
- Expose the application using a Kubernetes Service
- Verify successful deployment

---

## 📊 Phase 3: Monitoring

Monitor application health and infrastructure using industry-standard monitoring tools.

### Tools Used

- **Prometheus** for metrics collection
- **Grafana** for dashboards and visualization

### Features

- Application metrics
- Cluster monitoring
- Resource utilization
- Real-time dashboards

---

## 🔒 Phase 4: DevSecOps Security

Integrate security into the CI/CD pipeline.

### Security Tools

- **Trivy** – Container image vulnerability scanning
- **OWASP Best Practices** – Secure application deployment

### Security Checks

- Image vulnerability scanning
- Dependency analysis
- Secure deployment practices
- Continuous security monitoring

---

## 📂 Project Architecture

```text
                GitHub Repository
                       │
                       ▼
                   Jenkins CI/CD
                       │
      ┌────────────────┴────────────────┐
      ▼                                 ▼
 SonarQube Analysis              Trivy Security Scan
      │                                 │
      └────────────────┬────────────────┘
                       ▼
                Docker Image Build
                       │
                       ▼
             Push to Container Registry
                       │
                       ▼
            Amazon EKS Kubernetes Cluster
                       │
                       ▼
                 Book My Show App
                       │
                       ▼
         Prometheus + Grafana Monitoring
```

---

## 🎯 Learning Objectives

- Implement a complete DevSecOps pipeline
- Automate build and deployment using Jenkins
- Containerize applications with Docker
- Deploy applications on Kubernetes (Amazon EKS)
- Monitor applications using Prometheus & Grafana
- Perform vulnerability scanning with Trivy
- Apply OWASP security best practices

---

## 📸 Screenshots

> Added screenshots :

---

## ⭐ Support

If you found this project helpful, don't forget to **⭐ Star** the repository.
