# command of kubernetes(Kind)
- kind create cluster --name <name>
- kind delete cluster -n <name>


# kubectl commands
- kubectl get nodes
- kubectl get pods
-  kubectl run nginx --image=nginx --port=80
- kubectl describe pod nginx
- kubectl logs mongo-pod
- kubectl delete pod mongo
- kubectl delete pod nginx
- kubectl apply -f rs.yml
- kubectl run nginx-pod --image=nginx --labels="app=nginx"
-  kubectl delete rs nginx-deployment-576c6b7b6
- kubectl get rs
- kubectl get pods
-  kubectl rollout history deployment/nginx-deployment(History of deployment)
- kubectl rollout undo deployment/nginx-deployment(undo the last deployment)
- kubectl get pods -owide

