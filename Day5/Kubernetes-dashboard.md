# Install Dasboard
```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.0.5/aio/deploy/recommended.yaml
```
# Create dashboard-admin-sa.yml file and copy below content and run this file
https://github.com/arjunachari12/k8s-learn/blob/main/dashboard-admin-sa.yml
```
kubectl apply -f dashboard-admin-sa.yml
```

# Create token and copy the output
```
kubectl -n kubernetes-dashboard create token admin-user
```

# Run Proxy
```
kubectl proxy
```
# Access Dashboard
http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/
