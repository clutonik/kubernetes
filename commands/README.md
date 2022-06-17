# Basic commands

The way we interact with a kubernetes cluster is through the kubectl commands which uses the
kubernetes API under the hood.

- Get nodes in a kubernetes cluster:
  - `kubectl get nodes`
- Get pods in a kubernetes cluster:
  - `kubectl get pods`
- Get services in a kubernetes cluster:
  - `kubectl get services`
- Get deployments in a kubernetes cluster:
  - `kubectl get deployments`
- Get replicasets in a kubernetes cluster:
  - `kubectl get replicasets`
- Get persistentvolumes in a kubernetes cluster:
  - `kubectl get persistentvolumes`
- Get persistentvolumeclaims in a kubernetes cluster:
  - `kubectl get persistentvolumeclaims`
- Get configmaps in a kubernetes cluster:
  - `kubectl get configmaps`
- Get secrets in a kubernetes cluster:
  - `kubectl get secrets`
- Get ingresses in a kubernetes cluster:
  - `kubectl get ingresses`
- Get cronjobs in a kubernetes cluster:
  - `kubectl get cronjobs`
- Get jobs in a kubernetes cluster:
  - `kubectl get jobs`
- Get daemonsets in a kubernetes cluster:
  - `kubectl get daemonsets`

## Commands to work with pods

- Describe a pod:
  - `kubectl describe pod <pod-name>`
- Get logs of a pod:
  - `kubectl logs <pod-name>`
- Get the pod definition in yaml:
  - `kubectl get pods <pod-name> -o yaml`
