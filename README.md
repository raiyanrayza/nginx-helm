# nginx-helm

## Nginx Application Deployment with Kubernetes and Helm

### Overview

This project demonstrates deploying an Nginx application on a Kubernetes cluster using Minikube. The process involves building a Docker image, storing it in AWS ECR, and deploying the application with Kubernetes YAML files. Additionally, a Helm chart is included for simplified management.

### Instructions

1. **Minikube Setup:**
   - Install Minikube.
   - Start Minikube with `minikube start`.

2. **AWS ECR Setup:**(Not Used here)
   - Install AWS CLI.
   - Configure AWS CLI.
   - Create an ECR repository.

3. **Build and Deploy:**
   - Build and push the Nginx Docker image to ECR.
   - Apply Kubernetes deployment YAML.
   - Expose the service and access the Nginx welcome page.

### Helm Chart

- A Helm chart (`nginx-chart`) is included for easy deployment and management of the Nginx application. Customize values in `values.yaml` and templates `deployment.yaml` `service.yaml` and install using Helm.

For detailed steps, refer to the full documentation. If you encounter any issues or have questions, feel free to reach out.
