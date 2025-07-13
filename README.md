# flask-DevOps-CI/CD-pipeline
## 🔧 Project Structure

```text
flask-devops/
├── app.py                # Flask application
├── Dockerfile            # Container definition
├── requirements.txt      # Python dependencies
├── k8s/
│   ├── deployment.yaml   # Kubernetes Deployment
│   └── service.yaml      # Kubernetes Service
└── .github/
    └── workflows/
        └── deploy.yaml   # GitHub Actions CI/CD pipeline

