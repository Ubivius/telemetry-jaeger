# Telemetry-Jaeger

A tool that aggregates network traces for the cluster

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

- jaeger · helm/jaegertracing (https://artifacthub.io/packages/helm/jaegertracing/jaeger)

Once Helm is set up properly, add the repo as follows:

## Get Repo Info

```console
$ helm repo add jaegertracing https://jaegertracing.github.io/helm-charts
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `jaeger`:

```console
$ helm install jaeger --version <version> jaegertracing/jaeger -f chart/values.yaml
```

## Uninstalling the Chart

To uninstall/delete the jaeger deployment:

```console
$ helm delete jaeger
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
