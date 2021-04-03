# homelab-k3s

Repository to provide GitOps to (homelab) Raspberry Pi-based k3s cluster, using Flux.

## Notes:

- Installing CRD's for cert-manager doesn't seem to work. You can apply them manually:

```
kubectl apply -f https://github.com/jetstack/cert-manager/releases/download/v1.2.0/cert-manager.crds.yaml
```