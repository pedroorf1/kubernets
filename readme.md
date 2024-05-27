*COMMANDS*
- kubectl apply -f <filename>
- kubectl get pods
- kubectl ger deployment
- kubectl delete deployment <deployment-name>
- kubectl expose deployment <app-html-deployment> --type=LoadBalancer --name=<app-html> --port=80
- kubectl get service
- para minikube pegar ip externo do LoadBalacer: - minikube service --url app-html

kubectl expose deployment app-html-deployment --type=LoadBalancer --name=app-html --port=80
kubectl expose deployment app-phpadmin-deployment --type=LoadBalancer --name=app-phpadmin --port=80
