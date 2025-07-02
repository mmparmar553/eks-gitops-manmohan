# GitOps Demo with ArgoCD

This repository contains Kubernetes manifests for our GitOps demo using ArgoCD.

## Structure
- `nginx-app/` - Nginx microservice manifests
- `argocd-apps/` - ArgoCD application definitions

## Workflow
1. Make changes to manifests
2. Commit and push to Git
3. ArgoCD automatically syncs changes to EKS cluster
