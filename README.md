# Kubernetes DevSecOps CICD Project Using Github Actions and ArgoCD
# Project Overview
This project aims to streamline deployment and management activities on AWS using a combination of IAM, Terraform, GitHub Actions, and Kubernetes
![gif2](https://github.com/cloudcore-hub/reactjs-quiz-app/assets/88560609/a0dfce93-3bde-45af-b82a-d7c9e2c47294). Also stored the terraform.tfstate file in a s3 bucket 
# Key Components
- IAM User Setup: Creation of an IAM user with necessary permissions for AWS deployment and management.
- Infrastructure as Code (IaC): Utilization of Terraform and AWS CLI for setting up the Jumphost server (EC2 instance) on AWS .Used yet another Github workflow to automate it https://github.com/satyazzz123/iac_code.git .
- GitHub Actions Configuration: Configuration of essential GitHub Actions workflows, including Snyk, Docker, Sonarqube, Terraform, Kubectl, AWS CLI, and Trivy.
- EKS Cluster Deployment: Deployment of an Amazon EKS cluster using eksctl commands.
- Load Balancer Configuration: Configuration of AWS Application Load Balancer (ALB) for the EKS cluster.
- Dockerhub Repositories: Automatic creation of repositories for frontend and backend Docker images on Dockerhub.
- ArgoCD Installation: Setup of ArgoCD for continuous delivery and GitOps.
- Sonarqube Integration: Integration of Sonarqube for code quality analysis in the DevSecOps pipeline.
- Snyk Integration: Integration of Snyk for vulnerability scanning and dependency management analysis in the DevSecOps pipeline.
- Trivy Integration: Integration of Trivy for container image and filesystem vulnerability scanning in the DevSecOps pipeline.
- GitHub Action Pipelines: Creation of GitHub Action pipelines for deploying backend and frontend code to the EKS cluster.
- Monitoring Setup: Implementation of monitoring for the EKS cluster using Helm, Prometheus, and Grafana.
- ArgoCD Application Deployment: Deployment of the Three-Tier application, including database, backend, frontend, and ingress components, using ArgoCD.
- DNS Configuration: Configuration of DNS settings for application accessibility via custom subdomains using Route53.
- Data Persistence: Implementation of persistent volume and persistent volume claims for database pods to ensure data persistence.
- Deploying the Frontend ,Backend and Database with Proper secret management.

## Here are the Details of the Project


![Screenshot from 2024-04-01 22-04-53](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/75199f85-b248-4465-aa7b-a5ed4786d5f4)
![Screenshot from 2024-04-01 22-03-06](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/b80af01e-c63e-4818-befd-43b423b81475)
![Screenshot from 2024-04-01 22-03-16](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/917e03b4-2617-4799-9417-4fb66330d66f)
![Screenshot from 2024-04-01 22-03-23](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/c5b7f429-1d04-4896-9bd0-0080748d2349)
![Screenshot from 2024-04-01 22-03-48](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/15dadef7-4949-414b-aad5-8ee1bb9a852b)
![Screenshot from 2024-04-01 22-04-09](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/af2fe144-8ca4-4380-b4a0-7cc384c157e7)
![Screenshot from 2024-04-01 22-05-04](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/3c348b97-6a64-4827-8676-c829f34bf671)
![Screenshot from 2024-04-01 22-06-30](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/cefdcee1-e218-484a-a815-9b20d5335af4)
![Screenshot from 2024-04-01 22-07-02](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/bf001afb-d1b6-49c8-a4c8-28b2f1f70af0)
![Screenshot from 2024-04-01 22-10-22](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/886372ba-05bf-486b-919b-a9e77463a92a)
![Screenshot from 2024-04-01 22-05-29](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/87f9753f-6137-4590-b81b-bf98cd924c92)
![Screenshot from 2024-04-01 22-05-37](https://github.com/satyazzz123/react-quiz-EKS-deployment/assets/105061492/f7727d29-31e0-4cb2-ad37-35072aa34a59)








# Conclusion and Monitoring
This project concludes with a summary of key achievements and ongoing monitoring of the EKS cluster’s performance using Grafana


