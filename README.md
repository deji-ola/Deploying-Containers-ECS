# 🚢 Deploying Containers to AWS ECS

This project demonstrates how to containerize an application using Docker and deploy it to Amazon ECS (Elastic Container Service) using Fargate.

## 📦 Tools & Technologies
- Docker
- Amazon ECS
- AWS Fargate
- ECR (Elastic Container Registry)
- AWS CLI / AWS Console

## 🚀 Project Overview
The goal is to:
- Containerize a sample application
- Push the image to AWS ECR
- Deploy it using ECS (Fargate launch type)
- Expose the app publicly via a load balancer

## 🧰 Setup Instructions

1. **Build Docker Image**
   ```bash
   docker build -t ecs-demo-app .
