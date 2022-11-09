# commands that are used in this video.

```
brew install kubectl
brew install minikube
```
++++++++++++++++++++++++++++++++++++++
```
minikube start
kubectl get pod
kubectl apply -f mongo-config.yaml
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f webapp.yaml
kubectl get pod
kubectl get configmap
kubectl get secret
kubectl get svc
minikube ip
kubectl get node -o wide
```

```
minikube service webapp-service
```
++++++++++++++++++++++++++++++++++++++
```
kubectl delete deployment --all
```
```
kubectl delete secret --all
```