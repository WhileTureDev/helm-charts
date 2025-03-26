# Helm Setup for Kubernetes

## Add Open WebUI Helm Repository:
```shell
helm repo add open-webui https://open-webui.github.io/helm-charts
helm repo update
```

## Install Open WebUI Chart:
```shell
helm install open-webui open-webui/open-webui -n open-webui --create-namespace -f values.yaml
```