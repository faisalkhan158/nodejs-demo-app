# 🚀 DevOps Task 1 - CI/CD Pipeline using GitHub Actions

📌 Objective:
Automated the build and deployment of a Node.js web application using GitHub Actions and Docker.

🛠️ Tools & Technologies:
- GitHub & GitHub Actions
- Node.js
- Docker
- DockerHub

🔄 CI/CD Workflow:
This pipeline is triggered on every push to the `main` branch and follows these automated steps:

1. Checkout Code – Fetch the latest code from the repository  
2. Authenticate with DockerHub – Secure login using GitHub Secrets (`DOCKER_USERNAME`, `DOCKER_PASSWORD`)  
3. Build Docker Image – Build a Docker image for the Node.js app  
4. Push to DockerHub – Push the built image to my DockerHub repository


📦 DockerHub Repository:
🔗 [faisalkhan15/nodejs-demo-app](https://hub.docker.com/repository/docker/faisalkhan15/nodejs-demo-app)

✅ Status:
CI/CD pipeline is working perfectly with automatic build and push to DockerHub on every push to the main branch.
