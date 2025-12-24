# React Application Deployment on Kubernetes

## 📌 Overview
This project demonstrates how to deploy a React web application on Kubernetes using Docker, Deployment, and Service objects.  
The application is containerized, deployed on Minikube, and exposed using a LoadBalancer service.

---

## 🏗 Architecture
User → Kubernetes Service (LoadBalancer) → Deployment → Pod (React App Container)

---

## 🛠 Tech Stack
- React
- Docker
- Kubernetes
- Minikube
- Nginx

---

## ☸️ Kubernetes Concepts Used
- Pod
- Deployment
- Service
- Labels & Selectors
- Scaling
- Rolling Updates
- Rollback
- Self-Healing

---

## 🚀 Deployment Steps

### Start Minikube
```bash
minikube start

