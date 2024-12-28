# Flask Kubernetes Project

## Overview
This project demonstrates deploying a Flask application to Kubernetes using Minikube with NodePort for external access.

## Prerequisites
- Docker
- Minikube
- kubectl

## Steps

1. **Build the Docker Image**:
   ```bash
   docker build -t flask-app:latest ./app
