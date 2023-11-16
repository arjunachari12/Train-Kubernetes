## write manifest file configmap.yml, copy code from below link
https://github.com/arjunachari12/k8s-lrn/blob/main/configmap.yml

## Execute configmap.yml file using below command
```
kubectl create -f configmap.yml
kubectl get cm
kubectl describe cm game-demo
```

## write manifest file pod-configmap.yml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/pod-configmap.yml

## Execute pod-configmap.yml file using below command
```
kubectl create -f pod-configmap.yml
kubectl get pod
kubectl describe pod configmap-demo-pod
```
