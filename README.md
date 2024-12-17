# ArgoCD Web App

## Setup

- Create namespace for workflows,

```sh
kubectl create namespace argocd
```

- Install argo workflows,

```sh
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```

- Expose Argo Workflows UI Via Port-Fowarding.
  - Do this after the container `argo-server` is in the `Running` state,

```sh
kubectl port-forward svc/argocd-server -n argocd 8080:80
```
