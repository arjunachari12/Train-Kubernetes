```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update
```

# create ns
```
kubectl create ns prometheus
```
# Install prometheus 
```
helm install prometheus prometheus-community/prometheus --namespace prometheus
```
# port forward
```
export POD_NAME=$(kubectl get pods --namespace prometheus -l "app.kubernetes.io/name=prometheus,app.kubernetes.io/instance=prometheus" -o jsonpath="{.items[0].metadata.name}")
  kubectl --namespace prometheus port-forward $POD_NAME 9090
```
