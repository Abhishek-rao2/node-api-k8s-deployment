## 📦 Kubernetes Deployment

This app is deployed on a local Kubernetes cluster using Minikube.

- `deployment.yaml`: Runs 1 pod using Docker image `abhidochub123/node-api-app`
- `service.yaml`: Exposes the app via NodePort `30036`

Accessed via:
```bash
minikube service node-api-service

```

## 📸 Screenshots

### ✅ 1. Pod Running
![kubectl get pods](./screenshots/pods.png)

### ✅ 2. Service Exposed
![kubectl get svc](./screenshots/svc.png)

### ✅ 3. App in Browser
![App Output](./screenshots/browser.png)

