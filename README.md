# End-to-End-CI-CD-GitOps-Deployment-on-AWS-EKS

## 📌 Overview
This project demonstrates a complete DevOps workflow using AWS, Docker,
Kubernetes, Jenkins, Terraform, and ArgoCD to deploy a three-tier application
following GitOps principles.

## 🛠 Tools & Technologies
- AWS (EC2, EKS, IAM, VPC)
- Docker & Kubernetes
- Jenkins
- Terraform
- ArgoCD
- Prometheus & Grafana
- GitHub

## 🏗 Architecture
(Add architecture diagram image here)

## 🔄 CI/CD Workflow
1. Code pushed to GitHub
2. Jenkins triggers build & Docker image creation
3. Image pushed to DockerHub
4. ArgoCD syncs Kubernetes manifests
5. Application deployed on EKS
6. Monitoring via Prometheus & Grafana

## 🚀 Implementation Steps
1. Provision AWS infrastructure using Terraform
2. Build and push Docker image
3. Configure Jenkins pipeline
4. Deploy application on Kubernetes
5. Enable GitOps with ArgoCD
6. Monitor application health

## 📸 Screenshots
(Add screenshots of pipeline, ArgoCD sync, app running)

## 📚 Learnings
- Hands-on GitOps workflow
- CI/CD automation
- Kubernetes deployment strategies
- Infrastructure as Code best practices
