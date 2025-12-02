Ingress
This project automates the creation and deployment of an AWS EKS cluster with Fargate. It sets up the necessary IAM roles, installs the AWS Load Balancer Controller, and deploys the 2048 sample game app using Kubernetes manifests.

The repository includes:

Shell scripts to create the cluster, Fargate profile, IAM policies, and service accounts.

Kubernetes manifests for the 2048 game deployment.

Helm commands to install and configure the AWS Load Balancer Controller.

Users can run the scripts to provision the EKS cluster, deploy the app, and verify the deployment using kubectl commands.

Key Features:

Fully automated EKS cluster creation with Fargate.

Load Balancer setup for public access to applications.

Deployment of a sample Kubernetes application (2048 game).

Reproducible setup suitable for learning or testing EKS and ALB integrations.
