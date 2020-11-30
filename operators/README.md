## Katib charm operators
### Overview
This bundle encompasses the Kubernetes python operators (a.k.a. charms) for Katib (see [CharmHub](https://charmhub.io/?q=katib)). 

The Katib operators are python scripts that wrap the latest [Katib manifests](https://github.com/kubeflow/manifests/tree/master/katib), providing lifecycle management for each application, handling events (install, upgrade, integrate, remove). 

### Install

## Install applications
To install Katib charm operators run:
```
juju deploy < charm name >
```

For example: 
```
juju deploy katib-ui
```

## Install bundle 
To install the full Katib bundle run:
```
juju deploy < charm name >
```
