# Trendify DevOps CI/CD Project

## Project Overview

This project demonstrates an end-to-end DevOps CI/CD pipeline using GitHub, Jenkins, Docker, DockerHub, and Kubernetes.

The application was deployed into Kubernetes using Minikube and exposed through a Kubernetes service.

---

## Technologies Used

* Git & GitHub
* Docker
* DockerHub
* Jenkins
* Kubernetes
* Minikube
* AWS EC2

---

## Project Architecture

GitHub Repository
↓
Jenkins Pipeline
↓
Docker Build
↓
DockerHub Push
↓
Kubernetes Deployment
↓
Running Application

---

## Docker Commands

docker build -t balajithangapandi/trend-app:latest .
docker push balajithangapandi/trend-app:latest

---

## Kubernetes Commands

kubectl create deployment trend-app --image=balajithangapandi/trend-app:latest

kubectl expose deployment trend-app --type=NodePort --port=80

kubectl get pods

kubectl get svc

---

## Jenkins Pipeline Stages

1. Clone Repository
2. Build Docker Image
3. DockerHub Login
4. Push Docker Image

---

## GitHub Repository

Repository Link:
https://github.com/BalajiThangapandi/trend-devops-project

---
