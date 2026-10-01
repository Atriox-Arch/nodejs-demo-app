# nodejs-demo-app

## DevOps Task 1 - Node.js CI/CD Pipeline

This project demonstrates a CI/CD pipeline using GitHub Actions and Docker.

### What I built

- Created a Node.js application
- Added automated tests using Node.js test runner
- Created a Dockerfile to containerize the application
- Created a GitHub Actions CI/CD workflow
- Automated testing on every push to the `main` branch
- Built a Docker image automatically
- Pushed the Docker image to Docker Hub

### CI/CD Pipeline

The pipeline follows these steps:

1. Code is pushed to GitHub
2. GitHub Actions starts the workflow
3. Node.js is configured
4. Dependencies are installed
5. Automated tests are executed
6. GitHub Actions logs in to Docker Hub
7. Docker image is built
8. Docker image is pushed to Docker Hub

### Technologies Used

- Node.js
- GitHub
- GitHub Actions
- Docker
- Docker Hub

### Docker Image

Docker Hub repository:

`jayshinde15/nodejs-demo-app`

Docker image tag:

`latest`
