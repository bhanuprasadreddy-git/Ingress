# Ingress
This project automates the creation and deployment of an AWS EKS cluster with Fargate. It sets up the necessary IAM roles, installs the AWS Load Balancer Controller, and deploys the 2048 sample game app using Kubernetes manifests.

## The repository includes:

1.Shell scripts to create the cluster, Fargate profile, IAM policies, and service accounts.

2.Kubernetes manifests for the 2048 game deployment.

3.Helm commands to install and configure the AWS Load Balancer Controller.

4.Users can run the scripts to provision the EKS cluster, deploy the app, and verify the deployment using kubectl commands.

## Key Features:

1.Fully automated EKS cluster creation with Fargate.

2.Load Balancer setup for public access to applications.

3.Deployment of a sample Kubernetes application (2048 game).

4.Reproducible setup suitable for learning or testing EKS and ALB integrations.
