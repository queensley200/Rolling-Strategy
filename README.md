# Go Web Application

This is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.

## Running the server

To run the server, execute the following command:

```bash
go run main.go
```

The server will start on port 8080. You can access it by navigating to `http://localhost:8080/courses` in your web browser.

## Looks like this

![Website](static/images/golang-website.png)

# Rolling Strategy 

Implementing a **rolling deployment strategy** for Kubernetes using Helm and GitHub Actions, with support for blue/green and rolling updates.

---

## 🎯 Project Overview

This repository demonstrates best-practice deployment patterns for production-grade applications on Kubernetes:

- Uses **Helm charts** to package blue/green and standard rolling update deployments.
- Integrates **GitHub Actions CI** to:
  1. Build Docker image from source.
  2. Push to Docker Hub registry.
  3. Deploy to Kubernetes (blue/green or rolling) via Helm.
- Offers safe, zero-downtime deploys with environment toggles.

---

## 🛠️ Tech Stack

| Component           | Tool                         |
|--------------------|------------------------------|
| Containerization   | Docker                       |
| Kubernetes Runtime | Minikube (local)             |
| Package Manager    | Helm                         |
| CI/CD              | GitHub Actions               |
| Deployment Strategy| Blue/Green & Rolling Updates |

---

## 🚀 Quick Start

### 1. Prerequisites
Install the following tools:
```bash
brew install minikube kubectl helm
brew install --cask docker




