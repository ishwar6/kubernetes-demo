# Kubernetes Services

This folder contains example Kubernetes Service configurations.

## Contents

1. `nginx-service.yaml`: This is a service configuration for the Nginx deployment. The service exposes the Nginx Deployment to the internet on port 80.

## Usage

To create a service from a configuration file, use the `kubectl apply` command, like so:

```bash
kubectl apply -f nginx-service.yaml

