# prometheus-k8s

**Déploiement**
```sh
kubectl create namespace monitoring
kubectl apply -f prometheus/prometheus-application.yaml -n argocd
```

**Lister les TagRevision**
```sh
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update
helm search repo prometheus-community/prometheus --versions
```

