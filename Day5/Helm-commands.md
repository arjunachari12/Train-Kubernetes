# execute below helm commands
```
helm repo list
```
```
helm repo add bitnami https://charts.bitnami.com/bitnami
```
```
helm search repo bitnami
```
```
helm repo list
```
```
helm repo remove bitnami
```
```
helm repo add bitnami https://charts.bitnami.com/bitnami
```
```
helm search repo mysql
```
```
helm search repo database
```
```
helm search repo database --versions
```
```
helm search hub wordpresst
```
```
helm repo add brigade https://brigadecore.github.io/charts
```
```
helm install bitnami/mysql --generate-name
```
```
helm uninstall mysql-1612624192
```
```
helm status mysql-1612624192
```
```
helm install mydb bitnami/mysql
```
```
helm show values bitnami/mysql
```
```
kubectl get pods
```
```
helm list
```
```
kubectl create namespace mynamespace
helm istall mydb -n mynamespace
```
```
helm list --namespace mynamespace
```
```
helm uninstall mydb -n mynamespace
```
```
helm install happy-panda bitnami/wordpress
```
```
helm upgrade -f panda.yaml happy-panda bitnami/wordpress
```

