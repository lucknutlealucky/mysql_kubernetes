kubectl apply -f configmap.yaml
kubectl create -f secret.yaml
kubectl apply -f mysql-service.yaml
kubectl apply -f mysql-statefulset.yaml
kubectl get pod
