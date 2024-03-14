To use the rancher-monitoring chart for EdgeFlows, we need to:
- Make sure a local-path/local-storage volume with name "prometheus-cluster-monitoring-db-prometheus-cluster-monitoring-0" is created in advance

To use the rancher monitoring chart for Rancho Clusters, we need to:
- Make sure a PVC with the name "prometheus-cluster-monitoring-db-prometheus-cluster-monitoring-0" exists in advance


# to update helm chart. create the package and push it to the repo
```
helm package charts/cloudcore-provisioning
helm repo index .
```