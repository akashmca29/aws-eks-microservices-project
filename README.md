# AWS EKS Microservices Application

## Project Overview

This project demonstrates a microservices-based application deployed using Kubernetes on AWS EKS.

The architecture includes:
- Route 53 and CloudFront for domain and CDN
- Application Load Balancer with Ingress
- Amazon EKS cluster
- Kubernetes Pods and Services
- Amazon RDS / DynamoDB
- Prometheus and Grafana monitoring
- CloudWatch and SNS alerts

---

## Architecture Diagram

![Architecture Diagram](architecture-diagram.png)

---

## Project Flow

1. User accesses application via Route 53
2. CloudFront improves performance
3. ALB routes traffic to Kubernetes Ingress
4. Ingress routes traffic to services
5. Services route to Pods
6. Pods interact with database
7. Monitoring tools track performance
8. Alerts are sent via SNS

---
## Folder Structure 
aws-eks-microservices-app/
│
├── README.md
├── architecture-diagram.png
├── k8s-manifests/
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── ingress.yaml
│   └── configmap.yaml
├── docker/
│   └── Dockerfile
├── app/
│   ├── app.py
│   └── requirements.txt
├── monitoring/
│   ├── prometheus.yaml
│   └── grafana-setup.md
├── screenshots/
│   ├── eks-cluster.png
│   ├── pods.png
│   ├── services.png
│   ├── ingress.png
│   └── grafana-dashboard.png
├── deployment-steps.md
├── interview-questions.md
├── resume-points.md
└── cost-estimation.md

## Kubernetes Components

- Deployment
- Service
- Ingress
- ConfigMap

---

## Features

- Container Orchestration
- Microservices Architecture
- Auto Scaling (Pods)
- High Availability
- Monitoring and Alerts

---

## Resume Points

- Deployed microservices application on AWS EKS
- Configured Kubernetes deployments, services, and ingress
- Implemented monitoring using Prometheus and Grafana
- Integrated CloudWatch and SNS for alerting

---

## Interview Questions

1. What is Kubernetes?
2. What is EKS?
3. Difference between Pod and Service?
4. What is Ingress?
5. How scaling works in Kubernetes?
6. What is microservices architecture?
