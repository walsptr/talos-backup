# talos-backup

edit controlplane.yaml and worker.yaml
```
spec:
  machine:
    features:
      kubernetesTalosAPIAccess:
        enabled: true
        allowedRoles:
        - os:etcd:backup
        allowedKubernetesNamespaces:
        - default
```
