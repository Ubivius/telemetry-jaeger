# Jaeger Helm Chart

- jaeger · helm/jaegertracing (https://artifacthub.io/packages/helm/jaegertracing/jaeger)

## Get Repo Info

```console
$ helm repo add jaegertracing https://jaegertracing.github.io/helm-charts
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `jaeger`:

```console
$ helm install jaeger --version <version> jaegertracing/jaeger -f values.yaml
```

## Uninstalling the Chart

To uninstall/delete the jaeger deployment:

```console
$ helm delete jaeger
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
