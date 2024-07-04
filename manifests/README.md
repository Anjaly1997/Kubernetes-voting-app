# Kubernetes Voting Application

This project demonstrates the deployment of a cloud-native voting application on Amazon EKS. The application consists of a React frontend, a Go backend API, and a MongoDB database.

## Architecture

![Architecture Diagram](path/to/architecture-diagram.png)

## Deployment Steps

1. **Set up AWS EKS Cluster**: Follow the steps to create an EKS cluster.
2. **Deploy MongoDB**: Apply the MongoDB manifests.
3. **Deploy API**: Apply the API manifests.
4. **Deploy Frontend**: Apply the frontend manifests.

## Manifest Files

- `mongo-secret.yaml`: Secret for MongoDB credentials.
- `mongo-statefulset.yaml`: StatefulSet for MongoDB deployment.
- `mongo-service.yaml`: Service for MongoDB.
- `api-deployment.yaml`: Deployment for API.
- `api-service.yaml`: Service for API.
- `frontend-deployment.yaml`: Deployment for frontend.
- `frontend-service.yaml`: Service for frontend.

## How to Access

Once all components are deployed, use the external IP of the frontend service to access the application.
