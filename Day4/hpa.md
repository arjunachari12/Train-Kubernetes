## write manifest file hpa-deployment.yml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/hpa-deployment.yml

## Execute hpa-deployment.yml file using below command
```
kubectl create -f hpa-deployment.yml
kubectl get deployments
kubectl get rs
kubectl get pods
kubectl describe deployment hpa-demo
```
## write manifest file hpa.yml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/hpa.yml

## Execute hpa.yml file using below command
```
kubectl create -f hpa.yml
kubectl get hpa
kubectl describe hpa hpa-demo-autoscaler

