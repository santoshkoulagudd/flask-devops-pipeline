# flask-devops-pipeline
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

This ensures:
- Fixed width font
- No bold/heading formatting
- Clean display on GitHub

---

### ✅ How to Fix in Terminal

If you're on your EC2 instance:
```bash
cd ~/flask-devops
nano README.md
