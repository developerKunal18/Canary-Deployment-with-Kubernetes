# Canary Deployment with Kubernetes

A Kubernetes project demonstrating Canary Deployment for gradual application rollout.

## Features

- Kubernetes Deployments
- Gradual traffic rollout
- Easy rollback
- Zero-downtime deployment
- Production deployment strategy

## Technologies Used

- Python
- Flask
- Docker
- Kubernetes

## Installation

Deploy Version 1:

```bash
kubectl apply -f deployment-v1.yaml
```

Deploy Version 2:

```bash
kubectl apply -f deployment-v2.yaml
```

Deploy Service:

```bash
kubectl apply -f service.yaml
```
