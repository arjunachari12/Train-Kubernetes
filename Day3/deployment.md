## write manifest file helloworld-deployment.yml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/helloworld-deployment.yml

## Execute helloworld-deployment.yml file using below command
```
kubectl get deployments
kubectl get rs
kubectl get pods
kubectl get pods --show-labels
kubectl rollout status deployment/helloworld-deployment
kubectl set image deployment/helloworld-deployment k8s-demo=arjunachari12/k8s-demo:2
kubectl rollout history deployment/helloworld-deployment
kubectl rollout undo deployment/helloworld-deployment
kubectl edit deployment/helloworld-deployment
```
