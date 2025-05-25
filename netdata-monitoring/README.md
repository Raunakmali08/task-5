# Kubernetes Minikube Deployment

This repository contains Kubernetes YAML files to deploy an NGINX application locally using Minikube.

## Files

- `deployment.yaml`: Defines the NGINX deployment with 2 replicas.
- `service.yaml`: Exposes the deployment using a NodePort service.

## How to use

1. Start Minikube:
   ```bash
   minikube start

2. Deploy the app:
   kubectl apply -f deployment.yaml
   kubectl apply -f service.yaml

3. Check pods and services:
   kubectl get pods
   kubectl get services

4. Access the app via port-forward:
   kubectl port-forward service/nginx-service 9090:80


### Notes
    Make sure port 9090 is free or change it to a free port.

    This setup uses the Docker driver for Minikube.



---

### Step 3: Save and exit nano

- Press `Ctrl + O` then `Enter` to save.
- Press `Ctrl + X` to exit nano.

---

### Step 4: Add README.md and commit

```bash
git add README.md
git commit -m "Add README with instructions for Minikube NGINX deployment"




Author
This project was created and maintained by Raunak Mali.

GitHub

LinkedIn


---

Just copy-paste this into your README.md and save. Let me know if you want me to help with the Git commands next!
