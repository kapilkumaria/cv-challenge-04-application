# <u>DevOps Challenges</u> 🔥

Welcome to the **DevOps Challenges** repository, where I showcase my practical solutions to real-world DevOps problems. These challenges are designed to demonstrate my skills in automation, infrastructure management, CI/CD pipelines, and cloud engineering.

Below is a list of challenges with links to their respective repositories for detailed exploration:

1. [Week 1: **Full Stack Application with Monitoring and Logging ⚙️ 📊 🔥**](https://github.com/kapilkumaria/cv-challenge-01) - [Repo Here](https://github.com/kapilkumaria/cv-challenge-01)
   This challenge sets up a Full Stack application using Docker Compose, with a frontend, backend, database, and monitoring services. Traefik manages SSL certificates, path-based routing, and load balancing, while AWS Route53 handles DNS for domain integration. The project highlights container orchestration, secure routing, and system observability.

2. [Week 2: **Automate Deployment with Terraform and Ansible - Full Stack Application with Monitoring and Logging 🌐 📈 🔥**](https://github.com/kapilkumaria/cv-challenge-02) - [Repo Here](https://github.com/kapilkumaria/cv-challenge-02)  
   It focuses on automating the deployment of a full-stack application and its monitoring infrastructure using Terraform and Ansible. It provisions AWS resources, configures secure routing with Traefik, and deploys prebuilt Docker images for faster, scalable, and reproducible setups. Key improvements include end-to-end automation, reducing manual effort while ensuring robust and secure deployments.

3. [Week 3: **GitOps Workflow for Automation and Cost Optimization  💼 ✨ 🔥**](https://github.com/kapilkumaria/cv-challenge-03) - [Repo Here](https://github.com/kapilkumaria/cv-challenge-03)  
   This project implements a GitOps workflow to streamline infrastructure and application deployments while optimizing cloud costs using tools like InfraCost. It integrates Terraform and Ansible for infrastructure management and monitoring stack setup, ensuring automation through GitHub Actions CI/CD pipelines. A robust branching strategy separates infrastructure and application pipelines, enabling efficient collaboration and deployment.

4. [Week 4: **GitOps-Based Kubernetes Deployment 🔧 🔥**](https://github.com/kapilkumaria/cv-challenge-04) - [Repo Here](https://github.com/kapilkumaria/cv-challenge-04)
   Deploy a microservices application to Kubernetes using GitOps principles, automating workflows across three repositories. Use Terraform and Ansible for infrastructure provisioning, Dockerfiles and CI pipelines for container builds, and Kubernetes manifests for application deployment. This ensures streamlined, automated, and version-controlled operations.

Each challenge repository contains detailed documentation, scripts, and configurations for replicating the solutions.

---
---

# 💡 Week 4: GitOps-Based Kubernetes Deployment

This project deploys a multi-component microservices application to Kubernetes using GitOps principles and automating workflows across three repositories:

- **Infra Repo**: Manage cloud infrastructure provisioning and configuration with Terraform and Ansible.
- **Application Repo**: Handle microservices source code, Dockerfiles, and CI pipelines for Docker image management.
- **K8 Manifests Repo**: Store Kubernetes manifests for the microservices application (excluding ArgoCD manifests, which are managed by Ansible).

## Objectives

