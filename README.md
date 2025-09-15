# Deploying an App on EKS with Ingress

This repository contains documentation and examples for deploying an application on **Amazon EKS** (Elastic Kubernetes Service) using **Kubernetes Ingress** for external access.

## 📌 Prerequisites
- AWS account with necessary permissions
- [AWS CLI](https://docs.aws.amazon.com/cli/) installed and configured
- [kubectl](https://kubernetes.io/docs/tasks/tools/) installed
- [eksctl](https://eksctl.io/) installed
- Basic knowledge of Kubernetes and AWS

## 🚀 Steps Overview
1. Create an EKS cluster  
2. Configure `kubectl` with the cluster  
3. Deploy your application (Deployment + Service)  
4. Install an Ingress Controller (e.g., AWS Load Balancer Controller or NGINX)  
5. Configure Ingress resource  
6. Access your application via the generated DNS name  

## 📂 Repository Structure
