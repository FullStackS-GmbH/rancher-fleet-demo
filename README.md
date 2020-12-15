# Rancher / Fleet Example

## Single Cluster Deployment 

- no customization per cluster
- 1:1 deployment to every cluster

## Sample App

### GitRepo Ressource

```
kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: manifests
  namespace: fleet-local
spec:
  repo: https://github.com/FullStackS-GmbH/rancher-fleet-demo
  paths:
  - single-cluster/manifests
  ```
  
