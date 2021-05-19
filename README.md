# renning22 Helm Charts

[![Release](https://github.com/renning22/helm/workflows/Release/badge.svg)](https://github.com/renning22/helm/actions?query=workflow%3ARelease)

This repo contains renning22 Helm Charts:
* [bee](https://github.com/renning22/helm/tree/master/charts/bee)
* [beekeeper](https://github.com/renning22/helm/tree/master/charts/beekeeper)
* [eks-local-disk-provisioner](https://github.com/renning22/helm/tree/master/charts/eks-local-disk-provisioner)
* [geth-swap](https://github.com/renning22/helm/tree/master/charts/geth-swap)
* [tokenexporter](https://github.com/renning22/helm/tree/master/charts/tokenexporter)
* [ethexporter](https://github.com/renning22/helm/tree/master/charts/ethexporter)

## Enabling renning22 Helm repository

First you have to add our Helm repository like this:

```sh
$ helm repo add renning22 https://renning22.github.io/helm
```

Now You can run `helm search renning22` to see the charts.

Note that new versions might become available and you'll have to fetch these by doing `helm repo update`.
