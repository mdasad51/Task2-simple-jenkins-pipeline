# 📝 Django Notes App – CI/CD Pipeline with Jenkins, Docker & Azure
This project demonstrates a complete CI/CD pipeline for a Django-based Notes app using Jenkins, Docker, Docker Hub, and Azure VM. The pipeline is fully automated and integrated with a GitHub webhook to trigger on every push.

## Requirements
1. Python 3.9
2. Node.js
3. React

## 🚀 Deployment Architecture
```
GitHub → Jenkins (CI) → Docker Hub → Azure VM (CD using Docker Compose)

```

## ✅ Features of This Pipeline
---
- **📥 Code Checkout from GitHub**
- **🐳 Docker Image Build with the latest code**
- **☁️ Image Push to Docker Hub**
- **🧩 Automated Deployment on Azure VM using Docker Compose**
- **🔄 Webhook Integration for automatic pipeline triggering**

## 🛠️ Technologies Used
---
- **Django (Backend)**
- **Docker & Docker Compose**
- **Jenkins**
- **GitHub Webhook**
- **Azure VM (Ubuntu)**
- **Docker Hub**

## Installation
1. Clone the repository
```
https://github.com/mdasad51/Task2-simple-jenkins-pipeline.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
