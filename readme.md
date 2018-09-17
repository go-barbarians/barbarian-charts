### Barbarian
https://barbarians.io/

## Helm Charts
This repo contains the Helm charts for installing the Barbarian big data system on Kubernetes.

## Installing
Install the charts with the following commands. Note that some configuration parameters must be supplied.
- ```helm repo add http://charts.barbarians.io/barbarians```
- ```helm install barbarians/barbarian```

Alternatively consider installing [kubeapps](https://kubeapps.com/) on your cluster for a graphical installer.
