# Kubernetes etc.

Shell into a specific container in a pod:

```console
kubectl exec -i -t <POD> --container <CONTAINER> -- /bin/bash
```
Get logs from a container (easier) with https://github.com/wercker/stern `stern <container name>`

Redo a deployment:

```console
kubectl get deployment <NAME> -n default -o yaml | kubectl replace --force -f -
```

Redo a pod:

```console
kubectl get pod <NAME> -n default -o yaml | kubectl replace --force -f -
```
