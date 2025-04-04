**Application Deployment on Amazon EKS with Ingress**

This repository provides a step-by-step guide for deploying an application on Amazon EKS (Elastic Kubernetes Service) using AWS Application Load Balancer (ALB) Ingress Controller.

📌 Architecture
The deployment follows this architecture:

User → Load Balancer (ALB) → VPC → EKS Cluster → Worker Nodes → Pods (with Ingress)

<img width="829" alt="image" src="https://github.com/user-attachments/assets/dcfd4f2c-ecbd-4fab-b78a-8eea2576a458" />


🛠 Services Used
Amazon EKS (Elastic Kubernetes Service)

AWS ALB (Application Load Balancer)

VPC (Virtual Private Cloud)

Ingress Controller

Helm Package Manager
