
# 🐳 Kubernetes Mini Project: Frontend + Backend + Redis (Minikube)

This project is a basic application running locally in Kubernetes using **Minikube**, designed to help understand the core Kubernetes concepts: **Pods**, **Deployments**, **Services**, and internal **Networking**.

## Application Structure

- **Frontend (Nginx)** – serves a static HTML page that sends requests to the backend.
- **Backend (Python Flask / Node.js)** – simple API that communicates with Redis.
- **Redis** – stores a counter value that is incremented on each request.


## 🔧 How to Run the Project

1. Start Minikube:

minikube start --driver=docker

2. Create and apply the YAML files for:

- Redis Deployment & Service
- Backend Deployment & Service
- Frontend Deployment & Service

