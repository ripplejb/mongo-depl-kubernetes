## How to use?

1. Create secret and config.
```bash
kubectl apply -f secret.yaml
kubectl apply -f mongo-config.yaml
```
1. Create mongo deployment
```bash
kubectl apply -f mongo-depl.yaml
```
1. Create mongo express deployment
```bash
kubectl apply -f mongoex-depl
```
