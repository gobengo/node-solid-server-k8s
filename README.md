# node-solid-server-k8s

Kubernetes configuration for running [node-solid-server](https://github.com/solid/node-solid-server).

Uses [kustomize](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/), which is bundled with `kubectl`.

```
kubectl kustomize github.com/gobengo/node-solid-server-k8s
```

Or, if you have this cloned and are in the repository base directory:

```
kubectl kustomize .
```
