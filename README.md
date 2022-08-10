This repository hosts [Helm](https://helm.sh) charts.

## Add Helm repository

```bash
helm repo add helm-charts  https://i-frazzon.github.io/helm-charts/
helm repo update

## Install chart
```
```bash
helm upgrade --install app helm-charts/pgbouncer

