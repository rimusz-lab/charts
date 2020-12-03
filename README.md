# The Rimusz [Helm](https://helm.sh) Charts repository for demo purposes with ChartCenter.io

## Getting Started

### Install Helm

Get the latest [Helm release](https://helm.sh/docs/intro/install/).

### Add Helm chart repository

 ```console
 helm repo add center https://repo.chartcenter.io
 helm repo update
 ```

### Install some chart

To install the `security-sample-chart` chart with the release name `security-sample-chart`:

```console
helm upgrade --install security-sample-chart center/rimusz-lab-gh/security-sample-chart
```

Check `security-sample-chart` chart [readme](security-sample-chart/README.md) for more customization options.
