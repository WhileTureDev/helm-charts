## Add repository

```shell
helm repo add n8n https://riatlas.github.io/chart__n8n
helm repo update
```
## Install n8n

```shell
helm upgrad --install my-n8n n8n/n8n --version stable -n n8n --create-namespace -f values.yaml
```