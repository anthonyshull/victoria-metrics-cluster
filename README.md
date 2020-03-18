# VICTORIA METRICS CLUSTER

This Victoria Metrics cluster targets [microk8s](https://microk8s.io/).

You will need to have [metallb](https://metallb.universe.tf/) enabled for the `LoadBalancer` services.

```
%> microk8s.enable metallb
```

It should be trivial to convert to a cloud provider such as GCP.
Just change the persistent volume in `vmstorage-pv.yml`.

[Read More](https://github.com/VictoriaMetrics/VictoriaMetrics/tree/cluster) about Victoria Metrics cluster.

## USAGE
```
%> kubectl create -f .
```