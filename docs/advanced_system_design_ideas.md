# Advanced System Design Ideas

## Combine Multiple Concepts

### GitOps Pipeline

- Automate workflows triggered by Git changes.
- Deploy Helm charts and track ArgoCD syncs.

## Distributed Cron Jobs

- Use Argo Workflows to schedule distributed cron jobs.
- Example: Periodically scrape data, process it, and store results.

## Workflow for ML Pipelines

- Build a basic ML pipeline that:
  - Preprocesses data.
  - Trains a model (simulate with dummy steps).
  - Deploys the model.

## Dynamic ApplicationSet

- Deploy applications dynamically based on input from a REST API or Git.

## Kubernetes-native Backup System

- Automate backups for apps and databases with Argo Workflows.
