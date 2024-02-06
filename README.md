# kubernetes-knowledge-base

## minikube

Trying out locally on Fedora 39 using podman

https://minikube.sigs.k8s.io/docs/start/

```bash
minikube config set rootless true
minikube start --driver=podman --container-runtime=containerd
alias kubectl="minikube kubectl --"
```

## fedora

https://docs.fedoraproject.org/en-US/quick-docs/using-kubernetes/
