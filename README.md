<h1>Redis Cluster on Kubernetes</h1>

this is my repository for my personal notes

First create the service
```
kubectl create -f redis-svc.yaml
```

And then next create deployment for primary pod and replicas pods
```
kubectl create -f redis-deployment.yaml
```

you can access redis using ip from host and nodeport
