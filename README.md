# 🚀 CI/CD Pipeline with GitHub Actions + Docker

This project demonstrates a basic DevOps workflow:
- Unit testing a Node.js app
- Dockerizing the app
- Automating everything with GitHub Actions

## 📂 Structure
- `app/index.js`: Code logic
- `app/test.js`: Simple test
- `Dockerfile`: Build config
- `.github/workflows/ci.yml`: CI/CD pipeline

## 🔧 How to Run Locally
```bash
npm install
npm test
docker build -t test-image .
