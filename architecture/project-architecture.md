\# Kubernetes-Based Microservices Deployment Platform on AWS



\## Project Goal



Build a production-style microservices deployment platform using Kubernetes on AWS EC2 instances.



\## Architecture Components



\### Source Control



\* GitHub



\### CI/CD



\* Jenkins



\### Containerization



\* Docker



\### Infrastructure as Code



\* Terraform



\### Container Orchestration



\* Kubernetes (kubeadm)



\### Cloud Platform



\* AWS



\### Monitoring



\* CloudWatch



\## Kubernetes Cluster



\### Master Node



Responsibilities:



\* API Server

\* Scheduler

\* Controller Manager

\* Cluster Management



\### Worker Node 1



Runs application workloads.



\### Worker Node 2



Runs application workloads.



\## Microservices



\### User Service



Authentication and user management.



\### Product Service



Product catalog management.



\### Order Service



Order processing.



\### Frontend Service



User interface.



\## CI/CD Flow



Developer

→ GitHub

→ Jenkins

→ Docker Build

→ Docker Image Push

→ Kubernetes Deployment

→ Application Available



\## Monitoring Flow



Application

→ CloudWatch Agent

→ CloudWatch Metrics

→ CloudWatch Logs

→ Alerts



