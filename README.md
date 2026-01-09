# docker-file
just practice the docker basic 
# Dockerized Node.js Web Application

This project demonstrates how to containerize a Node.js web application using Docker.
It covers Docker image creation, container execution, and port mapping.

## 🚀 Features
- Node.js web application
- Dockerized using official Node base image
- Runs inside a container
- Accessible via browser using port mapping

## 🛠️ Tech Stack
- Node.js
- Docker
- JavaScript

## 📦 Docker Commands Used

```bash
docker build -t mywebapp:01 .
docker run -d -p 3000:3000 mywebapp:01
