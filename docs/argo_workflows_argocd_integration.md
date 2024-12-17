# Argo Workflows + ArgoCD Integration

## Description

Create workflows that deploy applications, roll back on failure, and manage progressive delivery.

### What to Include

- DAG workflows that,
  - Build container images (using Kaniko or BuildKit).
  - Deploy to Kubernetes clusters (via ArgoCD).
  - Run tests or health checks before marking deployments as successful.

### Features to Add

- CI/CD pipeline trigger via GitOps (push to Git triggers deployments).
- Rollback using ApplicationSet when a deployment fails.

### What You'll Learn:

- Workflow-driven deployments.
- Advanced GitOps principles.
- Building workflows to manage infra-as-code.
