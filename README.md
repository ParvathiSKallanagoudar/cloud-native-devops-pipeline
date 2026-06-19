# 🚀 Cloud Native DevOps Pipeline for Employee API
• Jenkins • Docker • Kubernetes • Prometheus • Grafana

## 📌 Project Overview

This project demonstrates an end-to-end Cloud Native DevOps CI/CD pipeline for a Spring Boot Employee API application. The pipeline automates code integration, application build, containerization, deployment, and monitoring using industry-standard DevOps tools.

## 🛠️ Tech Stack

* GitHub
* Jenkins
* Maven
* Docker
* Docker Hub
* Kubernetes (Minikube)
* Spring Boot
* Prometheus
* Grafana

---

## 🏗️ Architecture

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/fe76147d-bbf6-43b2-a0df-2eeb823c7045" />

---

## ⚙️ CI/CD Pipeline Stages

### 1️⃣ Checkout Code

Jenkins pulls the latest source code from the GitHub repository.

### 2️⃣ Build Application

Maven compiles the Spring Boot application and generates the executable JAR file.

### 3️⃣ Build Docker Image

A Docker image is created using the application artifact and Dockerfile.

### 4️⃣ Push to Docker Hub

The Docker image is tagged and pushed to Docker Hub for version control and deployment.

### 5️⃣ Deploy to Kubernetes

The application is deployed to a Kubernetes cluster using Deployment and Service manifests.

### 6️⃣ Monitor Application

Prometheus collects metrics from Spring Boot Actuator endpoints exposed by the application.

### 7️⃣ Visualize Metrics

Grafana dashboards visualize application and JVM metrics in real time.

---

## 📂 Repository Structure

```text
cloud-native-devops-pipeline
│
├── app/
│   └── employee-api/
│
├── kubernetes/
│   ├── deployment.yaml
│   └── service.yaml
│
├── Jenkinsfile
├── README.md
```

---

## ✨ Key Features

* Automated CI/CD Pipeline using Jenkins
* Docker Image Creation and Versioning
* Docker Hub Integration
* Kubernetes Deployment and Scaling
* Prometheus Metrics Collection
* Grafana Monitoring Dashboard
* Spring Boot Actuator Integration
* Real-Time Application Monitoring

---

## 📸 Project Screenshots

### Jenkins Pipeline Configuration
<img width="1920" height="868" alt="Jenkins Pipeline Configuration-1" src="https://github.com/user-attachments/assets/8970ddf1-accd-4fd8-9d20-6ca66344c70e" />


### Jenkins Successful Build

<img width="1920" height="875" alt="Jenkins Successful Build" src="https://github.com/user-attachments/assets/95e59767-3322-4a6d-8efb-eefdb0f60213" />


### Docker Hub Repository

<img width="1920" height="857" alt="Docker Hub Repository" src="https://github.com/user-attachments/assets/a7e7fb2e-14b5-4fd3-9fe9-2e06753a057c" />


### Kubernetes Deployment

<img width="1920" height="950" alt="Kubernetes Deployment" src="https://github.com/user-attachments/assets/1faf51b7-2f6e-4b2b-9e51-a6370ebae284" />


### Prometheus Targets

<img width="1920" height="632" alt="Prometheus Targets" src="https://github.com/user-attachments/assets/72cdeb6c-456e-410a-8242-070f5e4e4399" />


### Grafana Monitoring Dashboard

<img width="1920" height="861" alt="Grafana Monitoring Dashboard-1" src="https://github.com/user-attachments/assets/64b4e72d-2500-4914-9ccb-a75d2680df5a" />
<img width="1920" height="866" alt="Grafana Monitoring Dashboard-2" src="https://github.com/user-attachments/assets/ee6022f4-03d8-4f5d-ad61-789eb78c9a98" />


---

## 📊 Monitoring Metrics

The Grafana dashboard visualizes the following metrics:

* CPU Usage
* JVM Memory Usage
* Live JVM Threads
* HTTP Request Count

---

## ☸️ Kubernetes Resources

* Deployment
* Service (NodePort)
* Replica Management
* Pod Monitoring

---

## 🎯 Skills Demonstrated

* CI/CD Automation
* Containerization with Docker
* Kubernetes Orchestration
* Monitoring & Observability
* DevOps Best Practices
* Infrastructure Automation

---

## 📈 Project Outcomes

* Automated application build and deployment process
* Reduced manual deployment effort
* Improved application observability
* Real-time monitoring using Prometheus and Grafana
* End-to-end DevOps workflow implementation
* Production-style cloud-native deployment architecture

```
```
