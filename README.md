# DevOps Internship - Task 1

## Objective
Automate code deployment using a CI/CD pipeline using GitHub Actions.

## Tools Used
- GitHub
- GitHub Actions
- Node.js
- Docker
- Docker Hub

## Project Workflow

1. Developer pushes code to GitHub.
2. GitHub Actions workflow is triggered automatically.
3. Dependencies are installed.
4. Application tests are executed.
5. Docker image is built.
6. Docker image is pushed to Docker Hub.

## Files Included

- app.js
- package.json
- Dockerfile
- .github/workflows/main.yml

## Outcome

Successfully implemented a CI/CD pipeline that automatically builds and pushes a Docker image to Docker Hub whenever code is pushed to the main branch.

## Learning Outcomes

- Understanding of CI/CD concepts
- GitHub Actions workflow creation
- Docker image creation and management
- Secure secret management using GitHub Secrets
- Automated deployment practices