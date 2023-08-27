# Creat clusters in local machine with Kind and managing them with kubernetes
1-
kind create cluster --image=kindest/node:v1.25.3 --config=config.yaml
kubectl get nodes
docker ps

2-
kubectl apply -f deploy.yaml

3-
kubectl apply -f service.yaml

4-
kubectl get deployments
kubectl get pods
kubectl get replicasets
kubectl get svc

5-
kubectl delete pod iutcloud-69dc54f9c5-ch5h2

6-
kubectl port-forward deployment/iutcloud 3000:80
