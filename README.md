# kind

[kind](https://kind.sigs.k8s.io/) is a tool for running local Kubernetes clusters using Docker container “nodes”.

### clusters

`kind get clusters`

### create staging

`kind create cluster --name staging --config=staging.yaml`

### create production

`kind create cluster --name production --config=production.yaml`

### delete staging

`kind delete cluster --name staging`

### delete production

`kind delete cluster --name production`


