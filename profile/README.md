# Epinio  
### The Application Development Engine for Kubernetes
Go from **code → URL** with a single push. No containers. No hassle.

[![GitHub Release](https://img.shields.io/github/release/epinio/epinio.svg)](https://github.com/epinio/epinio/releases)
[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](LICENSE)
[![Slack](https://img.shields.io/badge/chat-Slack-4A154B.svg)](#community)
[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](https://docs.epinio.io/)

---

## 🚀 What is Epinio?

Epinio is a **lightweight, open-source Platform-as-a-Service** that installs into **any Kubernetes cluster** and gives developers a simple, fast **Code → URL** workflow.

- **Developers** push source code directly and get a live app URL in seconds  
- **Platform Engineers** get Kubernetes-native building blocks with sane defaults  
- **No lock-in:** Epinio uses generic Kubernetes resources and common OSS components  

---

## ✨ Key Features

### 🧑‍💻 Developer Happiness
- Zero Dockerfiles  
- Push your source code and let Epinio build & deploy automatically  
- Works with many languages and frameworks  

### ⚡ Fast & Lightweight
- Runs on any cluster: k3d, k3s, kind, EKS, GKE, AKS  
- Minimal footprint  
- Fast inner-loop development  

### 🧩 Flexible with Sane Defaults
- Uses standard Kubernetes primitives (Deployments, Services, Ingress)  
- Built on open-source components: Tekton, Buildpacks, and more  
- Bring your own ingress, registry, or build system  

### 🌐 Platform Interoperability 
- Integrate anywhere - Rancher & Backstage are just the beginning
- Digital sovereignty through interoperability

### 🙂 Amazing User Experience
- Built with User Experience as a top priority
- Not just an amazing Developer Experience - amazing UX for Platform Engineers & DevOps too

### 🔐 Secure by Design
- Built-in TLS  
- Built-in Git-based or API-based workflows  
- Clear RBAC boundaries between Developers and Operators  

---

## 🚀 Quick Start

The fastest way to try Epinio is on a local cluster (minikube recommended)

### **Prerequisites**
- Kubernetes 1.25+  
- `kubectl` installed  
- A default StorageClass  
- A local or remote container registry  

### Install Epinio
Full installation guide here: https://docs.epinio.io/installation/install_epinio


## 🏗️ Deploy Your First App

**1. Log in to Epinio**    
  Epinio login: https://epinio.YOUR-DOMAIN

**2. Create an Epinio app**    
`epinio app create` my-app

**3. Push your source code**    
`epinio push` my-app --path  

**4. Access your URL**    
`epinio app show` my-app

 💡 **Epinio automatically:**  
- Detects your language  
- Builds the container image  
- Creates the Kubernetes resources  
- Exposes your app via Ingress  
- Returns the live URL 🎉  

## 🧱 Architecture Overview
Epinio intentionally avoids inventing new abstractions - everything is powered by Kubernetes-native primitives!     

**API Server** - central control plane  
**Build Service** - builds containers with Buildpacks  
**Push Workflow** - orchestrates build + deploy steps  
**Kubernetes Resources** - Deployment, Service, Ingress  
**Ingress Controller** - Nginx, Traefik, or your choice  
**Container Registry** - local or external    

## 🧰 CLI Usage
See full CLI reference → https://docs.epinio.io/references/settings

## 🌍 Install Epinio on Any Cluster  
Use the same workflow everywhere!
- k3d / k3s  
- kind  
- Minikube  
- EKS  
- GKE  
- AKS  

## 🤝 Community
We'd love to have you involved!  

💬 **Slack:** Dedicated Epinio Slack community coming soon!   

For now, join us on the official #epinio channel on the Rancher Community Slack: https://rancher-users.slack.com  

🐛 **File Issues:** https://github.com/epinio/epinio/issues  

📚 **Documentation:** https://docs.epinio.io  

## 🧩 Contributing
We welcome all contributions--from documentation to features to ecosystem integrations!
See CONTRIBUTING.md for guidance.

## 📜 License
Epinio is licensed under the Apache 2.0 License.

## ⭐ Support the Project
If Epinio helps you, please consider giving it a ⭐ on GitHub -- it helps others discover the project!

