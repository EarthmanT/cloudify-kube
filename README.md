# cloudify-kube

An Active-Active Cloudify Manager Kubernetes Application.

## Prerequirements
  * A Kubernetes Cluster
  * A Cloudify License (It should be stored in this directory with name `license.yaml`.)

## Installation

```bash
chmod 755 scripts/*
export PATH=$PATH:$PWD/scripts
cloudify-manager-up
```

## Uninstallation

```bash
cloudify-manager-down
```
