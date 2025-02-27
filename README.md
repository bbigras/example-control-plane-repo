# Example Control Plane Repo

Deploy (need to run this twice)

```shell
kustomize build --enable-helm https://github.com/bbigras/example-control-plane-repo/bootstrap/overlays/default | kubectl apply -f -
```
