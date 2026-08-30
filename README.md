# Docker CI/CD Project

## 📌 Project Overview

This project demonstrates a complete **DevOps CI/CD workflow** using Git, GitHub, Docker, Jenkins, and AWS EC2.

The application is a simple HTML website that is containerized using Docker and automatically built and deployed through a Jenkins CI/CD pipeline on an AWS EC2 server.

---

## 🛠️ Technologies Used

- Git – Version control
- GitHub – Source code repository
- VS Code – Development environment
- Docker – Containerization
- Jenkins – CI/CD automation
- AWS EC2 – Cloud server
- HTML – Web application

---

## 🏗️ Project Architecture

```text
Developer
    │
    │  Write / Update Code
    ▼
VS Code
    │
    │ git add
    │ git commit
    │ git push
    ▼
GitHub Repository
    │
    │ Webhook / Jenkins Trigger
    ▼
Jenkins
    │
    ├── Build
    │
    ├── Test
    │
    ├── Docker Build
    │
    └── Deploy
    │
    ▼
Docker Container
    │
    ▼
AWS EC2 Server
    │
    ▼
Web Application
