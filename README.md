# CA Cloud Automation Project
##  Project Overview
This project demonstrates a complete CI/CD pipeline using GitHub Actions to automatically deploy a Dockerized NGINX web server to an AWS EC2 instance.
Whenever code is pushed to the main branch, GitHub Actions connects to the EC2 server via SSH and deploys the updated application automatically.
## 🛠 Technologies Used

 Git & GitHub
 GitHub Actions (CI/CD)
 AWS EC2 (Amazon Linux 2)
 Docker
 NGINX
 Ansible (for automation)

 ⚙️ Architecture Workflow
1. Developer pushes code to GitHub repository.
2. GitHub Actions workflow is triggered.
3. Workflow connects to EC2 via SSH.
4. Docker container is built/run.
5. NGINX web server is deployed.
6. Application becomes accessible via Public IP.

## Deployment Steps

###  Clone Repository
git clone  https://github.com/eniranjan23/ca-cloud-automation.git
