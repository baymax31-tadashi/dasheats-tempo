# 🍔 DashEats — Restaurant Management System

> A full-stack food ordering & restaurant management platform built with **Next.js 15** and **TypeScript**, deployed through a production-grade DevOps pipeline.

🌐 **Live:** [dasheats-tempo.vercel.app](https://dasheats-tempo.vercel.app/)

---

## ✨ Features
- 🛒 Browse menu & place food orders
- 🔧 Admin panel to manage menu items
- 📊 Analytics dashboard for orders & revenue
- 📱 Fully responsive UI

---

## 🛠️ Tech Stack

**Frontend:** Next.js 15, TypeScript, Tailwind CSS, shadcn/ui

**DevOps:**
| Tool | Role |
|------|------|
| 🔀 **Git** | Version control |
| 🔧 **Jenkins** | CI/CD pipeline (`Jenkinsfile`) |
| 📦 **Maven/Gradle** | Build & dependency management |
| 🐳 **Docker** | Containerization (`Dockerfile`, `docker-compose.yml`) |
| ☸️ **Kubernetes** | Container orchestration (`/k8s`) |
| 🤖 **Ansible** | Server automation & configuration (`/ansible`) |

---

## 📁 Project Structure
```
dasheats-tempo/
├── app/               # Next.js pages
├── components/        # UI components
├── ansible/           # Ansible playbooks
├── k8s/               # Kubernetes manifests
├── postman/           # API collections
├── Dockerfile
├── docker-compose.yml
└── Jenkinsfile
```

---

## ⚡ Getting Started

```bash
git clone https://github.com/baymax31-tadashi/dasheats-tempo.git
cd dasheats-tempo
pnpm install
pnpm dev
```

Or with Docker:
```bash
docker-compose up --build
```

---

## 🔄 CI/CD Pipeline
Jenkins pipeline runs: **Checkout → Build → Test → Dockerize → Deploy to K8s → Ansible Config**

---

> Built with ❤️ using Next.js · Docker · Kubernetes · Jenkins · Ansible
