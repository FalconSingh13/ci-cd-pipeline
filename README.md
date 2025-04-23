# CI/CD Pipeline with GitHub Actions

## 🔧 Stack
- Node.js
- Docker
- GitHub Actions
- (Optional) DockerHub or AWS EC2

## 📁 Project Structure
```
ci-cd-pipeline/
├── src/
│   └── index.js
├── Dockerfile
└── .github/
    └── workflows/
        └── deploy.yml
```

## 🚀 Run Locally
```bash
docker build -t ci-cd-node-app .
docker run -p 3000:3000 ci-cd-node-app
```

Visit: http://localhost:3000

## 🔄 CI/CD Workflow
- Trigger: Push to `main`
- Actions:
  - Checkout
  - Build Docker image
  - (Optional) Push to registry

## 📌 Next
Integrate deployment to EC2 or Kubernetes
