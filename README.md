# Cloud Native DevOps Pipeline for Employee API

## Project Overview

This project demonstrates an end-to-end Cloud Native DevOps CI/CD pipeline for a Spring Boot Employee API application using Jenkins, Docker, Kubernetes, Prometheus, and Grafana.

## Tech Stack

- GitHub
- Jenkins
- Maven
- Docker
- Docker Hub
- Kubernetes (Minikube)
- Prometheus
- Grafana
- Spring Boot

## Architecture

GitHub
↓
Jenkins Pipeline
↓
Maven Build
↓
Docker Image Build
↓
Docker Hub
↓
Kubernetes Deployment
↓
Prometheus Monitoring
↓
Grafana Dashboard

## Pipeline Stages

### 1. Checkout Code
Jenkins pulls source code from GitHub repository.

### 2. Build Application
Maven builds the Spring Boot application.

### 3. Build Docker Image
Docker image is created from the application.

### 4. Push to Docker Hub
Docker image is pushed to Docker Hub repository.

### 5. Deploy to Kubernetes
Application is deployed using Kubernetes Deployment and Service manifests.

### 6. Monitor Application
Prometheus collects metrics from Spring Boot Actuator endpoints.

### 7. Visualize Metrics
Grafana displays CPU, Memory, JVM Threads, and HTTP Request metrics.

## Project Screenshots

### Jenkins Pipeline Configuration
<img width="1920" height="868" alt="Jenkins Pipeline Configuration-1" src="https://github.com/user-attachments/assets/43c45519-6c6c-4c5d-bb2e-fb1fe93facc4" />


### Jenkins Successful Build
<img width="1920" height="875" alt="Jenkins Successful Build" src="https://github.com/user-attachments/assets/3ee3b12c-2d1f-4ccf-8fba-1d6e1f6ac5b4" />



### Docker Hub Repository
<img width="1920" height="857" alt="Docker Hub Repository" src="https://github.com/user-attachments/assets/2fdd2efa-136f-4e3b-9d15-0a171f7f81b5" />



### Kubernetes Deployment
<img width="1920" height="950" alt="Kubernetes Deployment" src="https://github.com/user-attachments/assets/e8248467-089b-422e-b75f-e38f0e48aebc" />



### Prometheus Targets
<img width="1920" height="632" alt="Prometheus Targets" src="https://github.com/user-attachments/assets/bcb3b26d-63db-4e96-a145-195973d1ae5b" />



### Grafana Monitoring Dashboard
<img width="1920" height="861" alt="Grafana Monitoring Dashboard-1" src="https://github.com/user-attachments/assets/f125fb22-b1cc-4530-b20d-8e47129a5189" />
<img width="1920" height="866" alt="Grafana Monitoring Dashboard-2" src="https://github.com/user-attachments/assets/c539dde7-c697-47e1-a641-f25a7830b17a" />

## Monitoring Metrics

- CPU Usage
- JVM Memory Usage
- Live JVM Threads
- HTTP Request Count

## Kubernetes Resources

- Deployment
- Service (NodePort)
- Replica Management
- Pod Monitoring

## Outcomes

- Automated CI/CD Pipeline
- Containerized Application Deployment
- Kubernetes Orchestration
- Real-time Monitoring and Observability
