# BIGAP Test Application

A simple test application to demonstrate GitOps deployment with ArgoCD.

## Architecture

- **Frontend**: Nginx serving a static HTML page
- **Deployment**: Kubernetes via ArgoCD
- **Ingress**: Traefik with automatic TLS

## Deployment

This application is automatically deployed via ArgoCD ApplicationSet that scans GitHub repos with the `argo-app` topic.

### Access

- **DEV**: https://test-app.dev.bigap.fr

## Features

- Simple HTML page
- Kubernetes Ingress with TLS
- ArgoCD automated deployment
- Helm chart for easy configuration
