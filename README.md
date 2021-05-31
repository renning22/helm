# renning22 Helm Charts

[![Release](https://github.com/renning22/helm/workflows/Release/badge.svg)](https://github.com/renning22/helm/actions?query=workflow%3ARelease)

This is a custom Helm Chart for deploying and operating a large number of Etheruem Swarm (bee) nodes in k8s. 

This is the main and only package:
* [ning-bee](https://github.com/renning22/helm/tree/master/charts/ning-bee)

Other files are just synced and kept unchanged from upstream offical.

## Enabling renning22 Helm repository

First you have to add our Helm repository like this:

```sh
$ helm repo add renning22 https://renning22.github.io/helm
```

Now You can run `helm search renning22` to see the charts.

Note that new versions might become available and you'll have to fetch these by doing `helm repo update`.
