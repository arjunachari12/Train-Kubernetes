## write manifest file helloworld-deployment-limit.yml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/helloworld-deployment-limit.yml

## Execute helloworld-deployment-limit.yml file using below command
```
kubectl apply -f helloworld-deployment-limit.yml
kubectl get deployments
kubectl get rs
kubectl get pods
kubectl describe pod <POD_NAME>
kubectl rollout status deployment/helloworld-deployment
```
