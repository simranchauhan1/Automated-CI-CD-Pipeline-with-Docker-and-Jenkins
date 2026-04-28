# Automated-CI-CD-Pipeline-with-Docker-and-Jenkins
This project demonstrates a complete end-to-end DevOps automation pipeline where a single Git push triggers the entire deployment lifecycle automatically.
## 🚀 Project Overview

The pipeline is designed to eliminate manual deployment steps and achieve Continuous Integration and Continuous Deployment (CI/CD) using Jenkins, Docker, GitHub, and AWS EC2.

---

## Workflow

- Developer pushes code to GitHub
- Jenkins automatically detects repository changes using webhook integration
- Jenkins pulls the latest code from GitHub
- Application build process starts automatically
- Automated testing is executed to validate code quality
- Docker image is built using the updated source code
- Docker image is pushed to Docker Hub registry
- Jenkins connects to AWS EC2 server
- Latest Docker image is pulled on EC2
- Existing container is replaced with the updated version
- Application becomes live automatically without manual intervention

---

## 🔧 Tech Stack

- GitHub – Source Code Management
- Jenkins – CI/CD Automation Server
- Docker – Containerization
- Docker Hub – Image Registry
- AWS EC2 – Application Hosting
- Linux – Server Environment
- Shell Scripting – Deployment Automation

---

## Architecture
<img width="1693" height="929" alt="Diagram" src="https://github.com/user-attachments/assets/ae0e0538-09a1-4e56-9b30-f94055f32f34" />


