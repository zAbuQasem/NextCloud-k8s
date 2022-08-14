# Installation
- Add repos
```bash
helm repo add nextcloud https://nextcloud.github.io/helm/
helm repo add nicholaswilde https://nicholaswilde.github.io/helm-charts/
helm repo update
```
- Install
```bash
helm install postgres nicholaswilde/postgres --values .\values-postgres
helm install nextcloud nextcloud/nextcloud --values .\values-nextcloud
```
