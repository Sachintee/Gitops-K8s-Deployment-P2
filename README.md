# GitOps Kubernetes Deployment using ArgoCD 🚀

## 📌 Overview
This repository implements **GitOps-based Continuous Deployment (CD)** using **ArgoCD**.
Kubernetes manifests stored here are continuously monitored and automatically synchronized with the cluster.

This repository complements the CI pipeline built using GitHub Actions.

---

## 🧠 What is GitOps?
GitOps uses **Git as the single source of truth** for infrastructure and application deployments.
ArgoCD ensures the Kubernetes cluster always matches the desired state defined in Git.

---

## 🧱 Architecture (CI + GitOps CD)

Code Repository (CI)
└── GitHub Actions
└── Docker Hub (Image)

GitOps Repository (CD)
└── ArgoCD
└── Kubernetes Cluster (Minikube)

---

## 🛠 Tech Stack
- Kubernetes
- ArgoCD
- GitHub
- Docker Hub
- Minikube

---

## 📂 Repository Structure

.
├── deployment.yaml
├── service.yaml
├── hpa.yaml
└── README.md

---

## ⚙️ Deployment Flow
1. Kubernetes manifests are updated in Git
2. Changes are pushed to GitHub
3. ArgoCD detects changes automatically
4. Cluster state is synchronized
5. No manual `kubectl apply` required

---

## 🔄 GitOps Features Enabled
- Auto Sync
- Self Healing
- Pruning of stale resources

---

## 🔗 Related CI Repository
Docker images are built and pushed by the CI pipeline:

👉 https://github.com/Sachintee/End-TO-End-CI-CD-Pipeline-using-GitHub-Actions.git

---

## 🎯 Key Learnings
- GitOps principles and workflows
- ArgoCD application management
- Kubernetes declarative deployments
- Real-world GitOps troubleshooting

---

## 👤 Author
Sachin
