# prerequisites
# Install

kubectl – A command line tool for working with Kubernetes clusters.

eksctl – A command line tool for working with EKS clusters that automates many individual tasks.

AWS CLI – A command line tool for working with AWS services, including Amazon EKS.

## Install using Fargate
# Run
```
eksctl create cluster --name eks-cluster --region us-east-1 --fargate
```
# 2048 App

## Create Fargate profile
# Run
```
eksctl create fargateprofile \
    --cluster eks-cluster \
    --region us-east-1 \
    --name alb-sample-app \
    --namespace game-2048
```

## Deploy the deployment, service and Ingress
# Run

```
kubectl apply -f https://raw.githubusercontent.com/kubernetes-sigs/aws-load-balancer-controller/v2.5.4/docs/examples/2048/2048_full.yaml
```

