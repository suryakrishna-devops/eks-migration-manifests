# EKS Client Migration Manifests

This repository contains reusable Kubernetes manifests for quickly migrating client applications to AWS EKS.

## Included

- Deployment template
- Service template
- ALB Ingress template
- Migration documentation

## Typical Flow

Client App → Docker Image → Fill Variables → Apply to EKS

## Variables Used

| Variable         | Meaning          |
|------------------|------------------|
| APP_NAME         | Application name |
| IMAGE_URI        | Docker image     |
| PORT             | App port         |
| DOMAIN           | Public domain    |
| REPLICAS         | Pod count        |
| ENV              | Environment      |

