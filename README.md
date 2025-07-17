# Node.js API Kubernetes Deployment

This project demonstrates a CI/CD pipeline with GitHub Actions, Docker, and Kubernetes (Minikube).

## 🧪 Tech Stack
- Node.js + Express
- Docker & DockerHub
- GitHub Actions
- Kubernetes (Minikube)
- kubectl

## ⚙️ What It Does
- Dockerizes a Node.js app
- Pushes it to DockerHub using GitHub Actions
- Deploys to local K8s (Minikube) with `kubectl`

## 📸 Proof (Screenshots)
All screenshots are under `/screenshots/`:
- ✅ Pods running
- ✅ Service exposed
- ✅ App accessed in browser

## 🔗 DockerHub
[View Docker Image](https://hub.docker.com/r/abhidochub123/node-api-app)

## 🚀 Live Deployment (Minikube only)
Accessible via NodePort:


## 📸 Screenshots

### ✅ 1. Pod Running
![kubectl get pods](./screenshots/pods.png)

### ✅ 2. Service Exposed
![kubectl get svc](./screenshots/svc.png)

### ✅ 3. App in Browser
![App Output](./screenshots/browser.png)

