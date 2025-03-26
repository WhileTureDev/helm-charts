# To install the chart with the release name searxng

```shell
helm repo add searxng https://charts.searxng.org
helm repo update
helm upgrade --install searxng searxng/searxng -f values.yaml
```

# To uninstall the searx deployment

```shell
helm uninstall searxng
```