# 🚀 DevOps Project: ZOMATO Clone App Deployment

In this **DevOps project**, I demonstrate how to deploy a **ZOMATO Clone Application** using a wide range of modern DevOps tools and cloud-native practices.  
This project covers **CI/CD, security scanning, containerization, monitoring, Kubernetes, and GitOps** end to end.

---

## 🔗 Repository
```
https://github.com/Jaganp-Devops/Zomato-App.git
```
## 🛠️ Tools & Services Used:

1. **GitHub** ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
2. **Jenkins** ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
3. **SonarQube** ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
4. **Docker** ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
5. **Kubernetes** ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
6. **Prometheus** ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
7. **Grafana** ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
8. **ArgoCD** ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
9. **OWASP** ![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)
10. **Trivy** ![Trivy](https://img.shields.io/badge/Trivy-00979D?style=flat-square&logo=trivy&logoColor=white)

---


## 🔁 CI/CD Pipeline Flow

1. Clean Jenkins workspace  
2. Clone source code from GitHub  
3. SonarQube analysis  
4. SonarQube Quality Gate (non-blocking)  
5. Install NPM dependencies  
6. OWASP Dependency vulnerability scan  
7. Trivy filesystem scan  
8. Build Docker image  
9. Push image to DockerHub  
10. Docker Scout security insights  
11. Deploy application using Docker container  
12. Email notification with scan reports  

---

## ⚙️ Jenkins Pipeline Highlights

- Declarative Jenkins pipeline  
- Secure credential management  
- Quality & security checks before deployment  
- Docker image lifecycle automation  
- Non-blocking scans for demo & learning  
- Email notification on every build  

---

## 🖥️ Infrastructure Overview

### Jenkins Server
- OS: Ubuntu 24.04  
- Instance Type: t2.large  
- Ports: 22, 8080  

### Monitoring Server
- Prometheus
- Node Exporter
- Grafana

---

## ☸️ Kubernetes Deployment (EKS)

- EKS cluster created using `eksctl`
- Managed node groups with auto-scaling
- Application deployed via Kubernetes manifests
- GitOps workflow using Argo CD
- Application exposed using NodePort / LoadBalancer

---

## 📊 Monitoring & Observability

- **Prometheus** scrapes metrics from:
  - Jenkins
  - EC2 / Node Exporter
  - Kubernetes nodes
- **Grafana** visualizes metrics using dashboards

---

## 📈 Final Outcome

- ✅ Fully automated CI/CD pipeline  
- ✅ Secure DevOps workflow with scanning  
- ✅ Docker image pushed to DockerHub  
- ✅ Application deployed on Docker & Kubernetes  
- ✅ Real-time monitoring with Grafana dashboards  

---

## 🧠 Key Learnings

- Jenkins CI/CD pipelines  
- Secure DevOps & vulnerability scanning  
- Docker & Kubernetes deployments  
- GitOps using Argo CD  
- Monitoring with Prometheus & Grafana  

---
