# 🚀 Docker Containerization – Cloud Native

This repository contains **Dockerized versions** of two projects: **Next.js** and **FastAPI**.  
The purpose of this assignment is to demonstrate **containerization, image creation, and deployment to Docker Hub**.

---

## 📌 Docker Hub Repositories



>  images are tagged with `latest`.

---

## 📁 Project Overview

## 📁 Projects Included

### 1️⃣ Next.js Docker (`nextjs-docker`)

* **Built Using:** Next.js  
* **Dockerized Using:** Node.js 22 Alpine  
* **Runs On Port:** 3000  
* **Description:** This containerized application serves a Next.js frontend, optimized for fast startup and lightweight deployment.

**Commands Used:**

```bash
# Build Docker image
docker build -t nextjs-docker .

# Run container
docker run -p 3000:3000 nextjs-docker
### 2️⃣ FastAPI Docker (`fastapi-docker`)

* **Built Using:** FastAPI  
* **Dependency Management:** uvicorn  
* **Dockerized Using:** Python 3.12 Slim  
* **Runs On Port:** 8000  
* **Description:** This containerized API provides backend services using FastAPI. It is optimized for rapid development, scalability, and efficient runtime performance.

**Commands Used:**

```bash
docker build -t fastapi-docker .
docker run -p 8000:8000 fastapi-docker
