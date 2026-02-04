
---

## 🛠 Technologies Used

- GitHub Actions
- Docker
- Amazon ECR
- Amazon ECS (Fargate)
- AWS IAM (OIDC)

---

## ✅ How to Verify Deployment

1. Check GitHub Actions → Workflow is green
2. Check Amazon ECR → New image with commit SHA
3. Check ECS Service → New task running
4. Open service public IP → Updated app content

---

## 📌 Interview-Ready Summary

> This pipeline builds and pushes Docker images to ECR and deploys them to ECS Fargate by creating a new task definition revision and updating the service using GitHub Actions with OIDC authentication.
