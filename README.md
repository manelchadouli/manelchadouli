# Manel Chadouli – Kubernetes DevOps Portfolio 🚀

[![Kubernetes CI/CD (No SSH)](https://github.com/manelchadouli/manelchadouli/actions/workflows/ci-cd.yaml/badge.svg)](https://github.com/manelchadouli/manelchadouli/actions/workflows/ci-cd.yaml)

This is my personal portfolio website deployed using **Kubernetes-first DevOps practices**.

## Key DevOps Concepts
- Docker containerization
- Kubernetes deployments (Deployment + Service)
- CI/CD with GitHub Actions
- No SSH access to any servers
- Infrastructure as code
- Ephemeral Kubernetes cluster in pipeline

## How it works
1. Website is containerized using Docker
2. Kubernetes Deployment runs the app
3. Service exposes the application
4. CI/CD pipeline deploys automatically
5. Workflow status shown above (badge)

## Tech Stack
- Docker
- Kubernetes (Kind)
- GitHub Actions
- Nginx

## Local Testing
1. Make sure Docker, kubectl, Kind installed
2. Build Docker image:
   ```bash
   docker build -t portfolio -f docker/Dockerfile .



