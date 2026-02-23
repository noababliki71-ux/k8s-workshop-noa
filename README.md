# k8s-workshop-noa

Kubernetes deployment of WordPress with MySQL.

## Components
- WordPress Deployment
- MySQL StatefulSet
- Ingress
- kube-prom-stack monitoring

## How to run
kubectl apply -f mysql.yaml
kubectl apply -f wordpress.yaml
kubectl apply -f ingress.yaml
