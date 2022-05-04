
# The deployment of stock application

## install

install minikube: https://minikube.sigs.k8s.io/docs/

## scripts

start minikube:

```bash
minikube start
```


start minikube dashboard:

```bash
 minikube dashboard
```

deploy to minikube

```bash

kubectl apply -f deployment.yaml
```
deploy service:


```bash

kubectl apply -f service.yaml
```
