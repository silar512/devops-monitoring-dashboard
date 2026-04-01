# 🚀 DevOps Monitoring Dashboard

## 📌 Overview
A production-style DevOps monitoring dashboard that displays real-time system metrics using AWS, Docker, and Bash scripting.

## ⚙️ Features
- Live CPU, Memory, Disk monitoring
- Dockerized deployment (Nginx)
- AWS EC2 hosting
- CI/CD pipeline (GitHub Actions)

## 🏗️ Architecture
User → Nginx (Docker) → Web UI → Bash Script → System Metrics

## 🛠️ Tech Stack
- AWS EC2
- Docker
- Nginx
- Bash
- HTML/CSS/JS

## 🚀 Deployment
```bash
docker build -t devops-dashboard .
docker run -d -p 80:80 devops-dashboard
## 🌐 Live Demo

👉 http://13.60.98.242
