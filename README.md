# DevOps Task 1: CI/CD Pipeline with GitHub Actions

## Objective
Automate code deployment of a Node.js app using GitHub Actions and Docker.

## Tools Used
- GitHub
- GitHub Actions
- Node.js
- Docker
- DockerHub

## Workflow
1. Push to `main` branch triggers GitHub Actions
2. Actions will:
   - Checkout code
   - Install dependencies
   - Run tests
   - Build Docker image
   - Push image to DockerHub

## Secrets Required
- `DOCKER_USERNAME`
- `DOCKER_PASSWORD`

## Setup Instructions
1. Clone the repo
2. Run `npm install`
3. Use `docker build` and `docker run` to test locally
