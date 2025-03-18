# CloudScaleApp-EKS

## Overview
CloudScaleApp-EKS is a **Three-Tier Web Application** built using **ReactJS, NodeJS, and MongoDB**, deployed on **AWS EKS** using Kubernetes. This project demonstrates infrastructure automation, CI/CD, and monitoring.

## Features
- **Frontend:** ReactJS
- **Backend:** Node.js with Express
- **Database:** MongoDB
- **Deployment:** AWS EKS using Kubernetes
- **CI/CD:** Jenkins & GitHub Actions
- **Monitoring:** Prometheus & Grafana

## Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Mayur-wagh4/CloudScaleApp-EKS.git
cd CloudScaleApp-EKS
```

### 2️⃣ Deploy Kubernetes Manifests
```bash
kubectl apply -f k8s-manifests/
```

### 3️⃣ Set Up CI/CD Pipeline (Optional)
- Configure `Jenkinsfile` for automated deployment.
- Modify `.github/workflows/pipeline.yml` for GitHub Actions.

## Usage
- **Access Application** → `http://your-load-balancer-url`
- **Check Kubernetes Pods** → `kubectl get pods -n workshop`
- **Monitor Logs** → `kubectl logs -f <pod_name>`

## Contribution
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

