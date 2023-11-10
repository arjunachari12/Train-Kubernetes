## write manifest file pod3.yml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/pod3.yml 

## Execute pod.yml file using below command
```
kubectl create -f pod3.yml
kubectl get pod
kubeclt describe pod pod3
```
## write manifest file pod3-service.yml, copy code from below link
https://github.com/arjunachari12/k8s-learn/blob/main/pod3-service.yml

## run below commands
```
kubectl get svc
minikube service helloworld-service --url
kubectl describe svc helloworld-service
kubectl describe svc 
Kubectl get svc
kubectl delete svc helloworld-nodeport-service.yml
```


