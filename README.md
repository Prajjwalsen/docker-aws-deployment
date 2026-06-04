# 🚀 Docker AWS Deployment

A Full-Stack Web Application containerized using Docker and deployed on AWS ECS (Fargate) with Amazon ECR and Application Load Balancer (ALB).

## 🌐 Live Demo

**Application URL:**

http://docker-aws-ALB-1560487339.ap-northeast-1.elb.amazonaws.com

---

## 📖 Project Overview

This project demonstrates the complete workflow of:

* Building a Full-Stack Application
* Containerizing applications using Docker
* Creating Multi-Stage Docker Builds
* Pushing Docker Images to Amazon ECR
* Deploying Containers on AWS ECS (Fargate)
* Configuring an Application Load Balancer (ALB)
* Managing Cloud Infrastructure on AWS

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Cloud & DevOps

* Docker
* Amazon ECR
* Amazon ECS (Fargate)
* AWS IAM
* Application Load Balancer (ALB)

---

## 📂 Project Structure

```bash
DOCKER-AWS/
│
├── Backend/
│   ├── public/
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── Frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── vite.config.js
│   └── tailwind.config.js
│
├── Dockerfile
├── .dockerignore
└── README.md
```

---

## 🏗️ Architecture

```text
React Frontend
      │
      ▼
Production Build
      │
      ▼
Node.js Backend
      │
      ▼
Docker Container
      │
      ▼
Amazon ECR
      │
      ▼
Amazon ECS (Fargate)
      │
      ▼
Application Load Balancer
      │
      ▼
Users
```

---

## 🐳 Docker Commands

### Build Docker Image

```bash
docker build -t docker-aws-app .
```

### Run Docker Container

```bash
docker run -p 4000:3000 docker-aws-app
```

Open:

```text
http://localhost:4000
```

---

## ☁️ AWS Deployment Workflow

1. Build Docker Image
2. Push Image to Amazon ECR
3. Create ECS Cluster
4. Create ECS Service
5. Configure Application Load Balancer
6. Deploy Application
7. Access Application through ALB URL

---

## ✨ Features

* Dockerized Full-Stack Application
* Multi-Stage Docker Build
* AWS ECS Deployment
* Application Load Balancer Integration
* Production Ready Frontend Build
* Scalable Cloud Infrastructure
* Container-Based Architecture

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Docker Fundamentals
* Docker Image Management
* Multi-Stage Docker Builds
* Amazon ECR Workflow
* Amazon ECS Deployment
* AWS IAM Basics
* Application Load Balancer Configuration
* Cloud Deployment Best Practices

---

## 🚀 Future Improvements

* CI/CD using GitHub Actions
* Custom Domain Integration
* HTTPS using AWS Certificate Manager
* MongoDB Integration
* User Authentication
* CloudWatch Monitoring
* Infrastructure as Code (Terraform)

---


## 👨‍💻 Author

### Prajjwal Sen

* GitHub: https://github.com/Prajjwalsen
* LinkedIn: https://www.linkedin.com/in/prajjwal-sen-20039531b

---

## ⭐ Acknowledgements

This project was built while learning Docker and AWS deployment concepts, focusing on containerization, cloud deployment, and DevOps fundamentals.

---

## 📜 License

This project is created for educational and learning purposes.
