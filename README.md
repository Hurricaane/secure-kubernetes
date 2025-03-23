# Kubernetes Secure Application

## Project Overview

Kubernetes Secure Application is a cloud-native application designed to demonstrate the best secure practices in a Kubernetes environment. It is also used to showcase up-to-date cluster deployment via Infrastructure as Code and GitOps, CI/CD pipelines (application and security testing, linting, etc.), monitoring and logging.

## Project Features

- **Secure Kubernetes Deployment**: the cluster is configured with the least privilege access, network policies, pod security standards etc.
- **Automated CI/CD Pipelines**: Github Actions and ArgoCD are used to test, lint and deploy the resources
- **Infrastructure as Code**: the cluster and resources are managed via Tofu and Helm
- **Runtime Security**: Falco is implemented for anomaly detection and Kyverno is used for policy enforcement
- **Logging and Monitoring**: the cluster will be monitored with Prometheus, Grafana and Loki
- **End-to-End encryption**: HTTP connections will be encrypted using TLS via Let's Encrypt and Cert-Manager
- **Role-Based Access Control (RBAC)**: this follows the principles of least privilege

## Technical Stack

- **Backend**: Golang
- **Frontend**: Nuxt.js
- **Orchestration**: Kubernetes
- **Infrastructure as Code**: Tofu
- **Security Tools**: Falco, Kyverno, Trivy, Snyk
- **Monitoring and Logging**: Prometheus, Grafana, Loki
- **CI/CD**: Github Actions, ArgoCD
