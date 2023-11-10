# Hands-on steps:
## Step 1: write manifest file helloworld_replicaset.yml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/pod3.yml 
## Step 2: Execute below command
```
kubectl create -f helloworld_replicaset.yaml
kubectl get rs
kubectl autoscale rs helloworld-controller --max=5
kubectl delete rs helloworld-controller
```

