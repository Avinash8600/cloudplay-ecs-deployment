# 🚀 CloudPlay – Containerized Application Deployment on AWS (ECR, ECS & CloudWatch)

A cloud-native web application deployed on Amazon ECS, with container images stored in Amazon ECR and application monitoring through Amazon CloudWatch.

---

## 🌟 Project Overview

CloudPlay demonstrates a complete AWS container deployment workflow using Docker, Amazon ECR, Amazon ECS, and CloudWatch. The application is containerized, stored in a private container registry, deployed on ECS, and monitored using AWS-native observability services.

---

## 🧠 Key Highlights

- 🐳 Containerized application using Docker
- 📦 Container image management with Amazon ECR
- 🚀 Application deployment on Amazon ECS
- 📊 Monitoring and logging with Amazon CloudWatch
- 🔄 Automated deployment workflow
- ☁️ AWS cloud-native architecture
- 📈 Scalable and production-ready deployment

---

## 🏗️ Architecture

```text
GitHub → Docker → Amazon ECR → Amazon ECS → CloudWatch → Users
```

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|-------------|
| Frontend | HTML, CSS, JavaScript |
| Containerization | Docker |
| Container Registry | Amazon ECR |
| Container Orchestration | Amazon ECS |
| Monitoring & Logging | Amazon CloudWatch |
| Cloud Platform | AWS |
| Version Control | Git & GitHub |

---

## 📦 Project Structure

```text
cloudplay-ecs-deployment/
│
├── index.html
├── style.css
├── script.js
├── Dockerfile
├── ecs-task-definition.json
└── README.md
```

---

## ⚙️ Deployment Workflow

1. Build the Docker image
2. Push the image to Amazon ECR
3. Create an ECS Task Definition
4. Deploy the application using ECS Service
5. Access the application through the ECS endpoint
6. Monitor logs and metrics using CloudWatch

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/your-username/cloudplay-ecs-deployment.git
cd cloudplay-ecs-deployment
```

### Build Docker Image

```bash
docker build -t cloudplay .
```

### Tag Image

```bash
docker tag cloudplay:latest <account-id>.dkr.ecr.<region>.amazonaws.com/cloudplay:latest
```

### Push to Amazon ECR

```bash
docker push <account-id>.dkr.ecr.<region>.amazonaws.com/cloudplay:latest
```

### Deploy to Amazon ECS

- Create ECS Task Definition
- Create ECS Service
- Launch the Application

---

## 📸 Screenshots

- Amazon ECR Repository 📦
- Amazon ECS Cluster 🚀
- ECS Service Running ✅
- CloudWatch Logs 📊
- CloudWatch Metrics Dashboard 📈
- Application UI 🌐

---

## 🎯 Resume Description

Developed CloudPlay, a containerized web application deployed on Amazon ECS using Docker and Amazon ECR, with centralized monitoring and logging through Amazon CloudWatch. Implemented cloud-native deployment practices and gained hands-on experience with AWS container services, observability, and scalable application hosting.

---

## 📈 Future Enhancements

- CI/CD using Jenkins or GitHub Actions
- ECS Service Auto Scaling
- AWS Secrets Manager Integration
- Grafana Dashboards
- Amazon EKS Migration

---

## 👨‍💻 Author

**Avinash Wagh**  
💼 Software Engineer | Cloud & DevOps Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
