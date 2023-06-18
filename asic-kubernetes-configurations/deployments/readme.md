# Kubernetes Deployments

This folder contains example Kubernetes Deployment configurations.

## Contents

1. `nginx-deployment.yaml`: This is a simple deployment configuration for an Nginx server. The deployment creates 3 replicas of Nginx.

## Usage

To deploy an application using its configuration, use the `kubectl apply` command, like so:

```bash
kubectl apply -f nginx-deployment.yaml
Replace nginx-deployment.yaml with the name of the configuration file for the deployment you want to create.

Make sure you are in the correct context for your Kubernetes cluster before applying the configurations. You can check your current context using kubectl config current-context and change it using 

kubectl config use-context

