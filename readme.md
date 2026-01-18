# 🚀 Docker Containerization – Cloud Native (Day 1)

This repository is submitted as part of the **Cloud-Native Computing (Day 1) Assignment**.  
The objective of this assignment is to containerize applications and publish Docker images to **Docker Hub**, demonstrating proficiency in Docker containerization and deployment.

---

## 📌 Submission Requirements

As required, the Docker images have been successfully built, tagged, and pushed to **Docker Hub**.  
The repository links are provided below for verification.

**Built using Next.js**
Dockerized using Node.js 22 Alpine
Runs on port 3000
Commands used:

docker build -t nextjs-docker .
docker run -p 3000:3000 nextjs-docker
**FastAPI Docker (fastapi-docker)**
Built using FastAPI
Dependency management with uv
Dockerized using Python 3.12 Slim
Runs on port 8000
Commands used:

docker build -t fastapi-docker .
docker run -p 8000:8000 fastapi-docker
Docker
Docker Desktop Images (Next.js & FastAPI)
Docker Desktop Containers (Both Running)
Docker Images Docker Containers
docker-images.png



