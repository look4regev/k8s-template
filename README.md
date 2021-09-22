# k8s-template
Template for kubernetes app, mainly for local tries

## Local setup using minikube
```
brew install minikube hyperkit
minikube config set driver hyperkit
minikube start
eval $(minikube docker-env)
```

## Deploy
```
kubectl apply -f deployment.yaml
```

## Future plans
1. Add an ingress using kong
2. Replace nginx with an http app built with docker
