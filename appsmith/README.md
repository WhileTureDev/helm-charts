# Install Appsmith

Follow these steps to install Appsmith:

1. Add the Appsmith Helm repository:

```shell
helm repo add appsmith https://helm.appsmith.com
```

2. Update the Helm repository:

```shell
helm repo update
```
3. Install Appsmith:

```shell
helm upgrade --install appsmith appsmith/appsmith -n appsmith --create-namespace -f values.yaml
```