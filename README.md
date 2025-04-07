# 🚀 DevOps Task 1 – CI/CD Pipeline using GitHub Actions

## 📌 Objective
Automated the build and deployment of a Node.js web application using GitHub Actions and Docker.

## 🛠️ Tools & Technologies
- GitHub & GitHub Actions  
- Node.js  
- Docker  
- DockerHub  

## 🔄 CI/CD Workflow
The CI/CD pipeline is triggered on every push to the `main` branch and performs the following steps automatically:

1. **Checkout Code** – Fetch the latest source code from the repository  
2. **Authenticate with DockerHub** – Secure login using GitHub Secrets (`DOCKER_USERNAME`, `DOCKER_PASSWORD`)  
3. **Build Docker Image** – Create a Docker image for the Node.js application  
4. **Push to DockerHub** – Push the image to the linked DockerHub repository  

## 📦 DockerHub Repository
🔗 [faisalkhan15/nodejs-demo-app](https://hub.docker.com/repository/docker/faisalkhan15/nodejs-demo-app)

## ✅ Status
CI/CD pipeline is functioning successfully — builds and pushes the Docker image on every push to the main branch.
