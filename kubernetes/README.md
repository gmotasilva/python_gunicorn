# Kubernetes deploy

To deploy this into a kubernetes system

Just use: 
```
kubectl apply -f ./hello-world.yaml -n $namespace
````

To access via por foward as the service is not exposed public:

```
kubectl port-forward --namespace $namespace svc/hello 8003:8003
```

