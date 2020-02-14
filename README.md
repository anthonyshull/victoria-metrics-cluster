# VICTORIA METRICS CLUSTER

This Victoria Metrics cluster targets [microk8s](https://microk8s.io/).
It should be trivial to convert to a cloud provider such as GCE.
Just change the persistent volume in `vmstorage-pv.yml`.
You'll probably want to change the services from NodePort to LoadBalancer as well.

[Read More](https://github.com/VictoriaMetrics/VictoriaMetrics/tree/cluster) about Victoria Metrics cluster.

## USAGE
```
%> kubectl apply -f .
```