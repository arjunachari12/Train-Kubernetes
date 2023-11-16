## write manifest file secrets.yaml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/secrets.yaml

## Execute secrets.yaml file using below command
```
kubectl create -f secrets.yaml
kubectl get secrets
kubectl describe secrets helloworld-secrets
```
## write manifest file database.yaml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/database.yml

## Execute database.yaml file using below command
```
kubectl create -f database.yaml
kubectl get pod
kubectl describe pod database
```
