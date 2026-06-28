# Hi, I'm Piriyajeishree Murali Naidu!

🎓 MS in Computer Science @ Northeastern University (2025–Present)  
☁️ Cloud / DevOps Engineer with 2+ years AWS production experience  
🔎 Seeking a 2026 Co-op in Site Reliability Engineering or Cloud Infrastructure roles focused on scalable systems and automation.

---

## Professional Snapshot

- 2+ years at Cognizant supporting AWS-based microservices
- Improved CI/CD deployment speed by 30% using Jenkins + AWS
- Reduced manual deployment effort by 35% via Terraform + ECS/Fargate
- Maintained 99.9% uptime across 40+ EC2 instances
- Improved release stability by 25% using CloudWatch monitoring & logging
- AWS Certified Cloud Practitioner

---

## Tech Stack

### Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

### CI/CD & Infrastructure as Code
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)

### Containers & Orchestration
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Amazon ECS](https://img.shields.io/badge/Amazon_ECS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

### Monitoring & Reliability
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white)

### Programming
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

---

## Featured Projects

### Foresight-ML: Corporate-Financial Distress Early Warning System

Ranked #1 of ~35 graduate teams at Google Cambridge MLOps Expo

**Python | Terraform | GitHub Actions | Airflow | MLflow | 
DVC | XGBoost | SHAP | GCP Cloud Run | Workload Identity Federation**

Infrastructure & CI/CD Lead — owned all architecture decisions, 
GCP IAM, and GitOps delivery strategy.

- Chose Airflow over Cloud Scheduler: needed multi-step DAG 
  dependencies, parallel branches (FRED + SEC ingestion), and 
  per-task failure isolation — not just cron triggers
- Chose Workload Identity Federation over static service account 
  keys: eliminated credential rotation risk and long-lived secret 
  exposure in CI
- Provisioned full GCP stack via Terraform: Cloud Run Jobs, GCS, 
  Artifact Registry, Secret Manager, IAM bindings
- Built 4 GitHub Actions workflows with Trivy container scanning, 
  Bandit, SonarCloud, pip-audit, mypy, and Slack release notifications
- Implemented DVC pipeline stages (split→train→evaluate) with GCS 
  remote — changing xgboost.yaml automatically reruns only affected 
  stages
- Debugged critical inference bug: mlflow.pyfunc.predict() returns 
  class labels, not probabilities — switched to native XGBoost 
  predict_proba()[:,1]; the kind of subtle failure that breaks 
  production silently

---

### ApplyFlow - Intelligent Job Application Optimization Platform (Ongoing)
**Python | FastAPI | Streamlit | Docker | Terraform | AWS ECS Fargate | RDS | GitHub Actions**

- Built an end-to-end job ingestion and tracking pipeline with PostgreSQL and a structured application outcome model
- Containerized services with Docker and deployed to AWS ECS Fargate with RDS PostgreSQL via Terraform
- Automated CI/CD pipeline with GitHub Actions, including linting, unit tests, and ECR image push
- Exposed health and metrics endpoints via FastAPI; built an interactive tracking dashboard with Streamlit
- Implemented CloudWatch custom metrics, alarms, and SNS email alerting for ingestion monitoring
- Designed multi-user SearchProfile support for personalized job filtering and scoring

---

### Signlingo - Sign Language to Text Conversion System
**Python | OpenCV | MediaPipe | Docker | AWS ECS**

- Real-time computer vision inference system
- Dockerized application for consistent deployments
- Managed container images in Amazon ECR
- Deployed services on ECS for scalable delivery
- Designed for accessibility-focused use cases

---

## What I'm Focused On

- Infrastructure as Code best practices
- Reliability engineering & observability
- Production-grade CI/CD pipelines
- Distributed systems & microservices architecture
- Cloud-native system design

---

## Connect With Me

- piriyajeishree410@gmail.com  
- LinkedIn: https://www.linkedin.com/in/piriyajeishree-murali  
- GitHub: https://github.com/piriyajeishree410  

---

 Always building. Always automating. Always improving reliability.
