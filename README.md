# Node.js Kubernetes Deployment Pipeline (Jenkins CI/CD)

End-to-end DevOps project demonstrating a complete CI/CD pipeline for a Dockerized Node.js application deployed on Kubernetes with monitoring, autoscaling, image scanning, and secret management.

## Key Features

CI/CD Pipeline (Jenkins) – Automates build, test, image scan, Docker image push, and Kubernetes deployment.

Containerization – Node.js app is Dockerized for consistent deployments.

Kubernetes Deployment – Application deployed on Kubernetes (Minikube) with Deployment, Service, and Ingress.

Autoscaling – Configured Horizontal Pod Autoscaler (HPA) for automatic scaling based on CPU load.

Monitoring – Integrated Prometheus and Grafana for performance and health monitoring.

Security – Integrated Trivy for image vulnerability scanning and Kubernetes Secrets for sensitive data.

Rollback Mechanism – Jenkins pipeline supports automatic rollback on deployment failure.
