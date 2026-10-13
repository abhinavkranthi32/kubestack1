# ☁️ Build Your Own Cloud

### Your Infrastructure. Your Rules. Your Cloud.

A hands-on learning project focused on building and managing your own cloud infrastructure using Kubernetes, K3s, GitOps, and self-hosted services.

The goal is to understand how modern cloud infrastructure works by deploying and managing applications on your own infrastructure instead of relying entirely on managed cloud platforms.

---

## 🚀 Overview

Cloud computing powers modern applications, but understanding what happens behind the scenes is just as important as using cloud services.

This project explores the fundamentals of building your own cloud environment, from setting up a Kubernetes cluster to exposing services, deploying applications, and implementing GitOps workflows.

Whether you're learning DevOps, exploring self-hosting, or experimenting with Kubernetes, this repository serves as a practical learning resource.

## ✨ What You'll Learn

- **Kubernetes & K3s:** Set up and manage lightweight Kubernetes clusters.
- **Cluster Configuration:** Prepare nodes, configure networking, and establish your cluster.
- **Service Exposure:** Explore different approaches to making applications accessible.
- **GitOps:** Understand declarative infrastructure and Git-based deployment workflows.
- **Argo CD:** Explore continuous delivery and application synchronization.
- **Application Deployment:** Deploy applications using Kubernetes manifests.
- **Monitoring:** Learn the fundamentals of monitoring and alerting.
- **Persistent Storage:** Understand storage options for stateful workloads.
- **CI/CD:** Explore automated build and deployment pipelines.
- **Infrastructure Management:** Learn how to troubleshoot and maintain your environment.

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Kubernetes | Container orchestration |
| K3s | Lightweight Kubernetes distribution |
| Helm | Kubernetes application packaging |
| Argo CD | GitOps continuous delivery |
| Cloudflare Tunnel | Secure service exposure |
| Git | Version control |
| YAML | Configuration and deployment manifests |
| Linux | Infrastructure and server administration |

The tools used depend on the particular deployment path you choose.

## 📁 Repository Structure

```text
build-your-own-cloud/
│
├── 01-cluster-setup/
│   ├── README.md
│   ├── configure-kubectl.md
│   ├── hardware-and-os.md
│   ├── install-helm.md
│   ├── install-k3s/
│   └── prepare-nodes.md
│
├── 02-expose-services/
│   ├── README.md
│   ├── option-a-cloudflare-tunnel.md
│   ├── option-b-public-ip.md
│   └── option-c-lan-only.md
│
├── 03-gitops/
│   ├── README.md
│   ├── app-of-apps.md
│   ├── bootstrap-argocd.md
│   ├── cluster-secrets.md
│   ├── understanding-kustomize.md
│   └── what-is-gitops.md
│
├── 04-deploy/
│   ├── README.md
│   ├── first-app.md
│   └── writing-manifests.md
│
├── 05-extras/
│   ├── README.md
│   ├── cicd-pipelines.md
│   ├── cloudflare-access.md
│   ├── monitoring-and-alerts.md
│   └── persistent-storage.md
│
├── references/
│   ├── diagrams/
│   ├── reference-links.md
│   ├── resetting.md
│   ├── troubleshooting.md
│   └── useful-tools.md
│
├── LICENSE
└── README.md
