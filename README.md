## 📦 Kubernetes Deployment

This app is deployed on a local Kubernetes cluster using Minikube.

- `deployment.yaml`: Runs 1 pod using Docker image `abhidochub123/node-api-app`
- `service.yaml`: Exposes the app via NodePort `30036`

Accessed via:
```bash
minikube service node-api-service

```
