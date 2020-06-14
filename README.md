### Basic commands

kubectl version --client

kubectl get pods

kubectl get svc

kubectl get deployments

kubectl get configmaps

kubectl get persistentvolumeclaim

kubectl get secrets

kubectl apply -f pod.yaml

kubectl apply -f deployment.yaml

kubectl apply -f service.yaml   

kubectl apply -f configmap.yaml

kubectl logs pod-exemplo

kubectl delete deployments --all

kubectl delete persistentvolumeclaim mysql-pv-claim 

kubectl create secret generic mysql-pass --from-literal=password='123455678'

kubectl exec -it POD_NAME bash


### Minikube

minikube version

minikube start

minikube status

minikube service nginx-service


### Mysql

kubectl exec -it POD_NAME bash

mysql -uroot -p
