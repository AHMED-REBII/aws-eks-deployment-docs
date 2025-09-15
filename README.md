# Deploying an App on EKS with Ingress

![AWS](https://img.shields.io/badge/AWS-EKS-orange) ![Kubernetes](https://img.shields.io/badge/Kubernetes-blue) ![Helm](https://img.shields.io/badge/Helm-3.0-blue)

This project demonstrates how to deploy a **Python 2048 game** on **AWS EKS** using **Fargate** and expose it to the internet with the **AWS Load Balancer Controller**.

---

## 📌 Prerequisites

Before you start, ensure you have installed and configured:

- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) – Kubernetes CLI
- [eksctl](https://eksctl.io/) – EKS cluster management CLI
- [AWS CLI](https://docs.aws.amazon.com/cli/) – AWS command-line interface

Configure AWS CLI with your credentials:

<details>
<summary>🔧 Configure AWS CLI</summary>

```bash
aws configure

## 🛠️ Deployment Steps

### 1️⃣ Create an EKS Cluster (Fargate)

```bash
eksctl create cluster --name demo-cluster --region us-east-1 --fargate
</details>
