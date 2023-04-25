# Description:
A demo for using mongo in k8s.

# Usage:
Go to admin powershell, run `minikube start`.
```
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f mongo-configmap.yaml 
kubectl apply -f mongo-express.yaml
```
Go back to admin powershell, run `minikube service mongo-express-service`, it will open browser automatically.
