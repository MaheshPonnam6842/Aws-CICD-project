## End to End MAchine Learning Project

1. Docker Build checked
2. Github Workflow
3. Iam User In AWS

## Docker Setup In EC2 commands to be Executed

#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 
ECR_REPOSITORY_NAME = 

## 🧹 Infrastructure Cleanup & Cost Awareness
```

The application was successfully deployed and validated using **Docker, AWS ECR, AWS EC2, and GitHub Actions**.

After verifying the complete CI/CD and deployment workflow, the cloud resources were **intentionally decommissioned** to avoid unnecessary ongoing cloud costs.

The entire deployment setup is fully **reproducible** using the provided Dockerfile, GitHub Actions workflow, and documented AWS configuration steps.

This reflects real-world, cost-conscious engineering practices commonly followed in production environments and concludes the end-to-end lifecycle of this project.
