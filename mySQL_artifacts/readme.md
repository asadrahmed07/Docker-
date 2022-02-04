# MYSQL kubernetes Artifacts
## Commands to follow 
1. Create namespace 
2. set the namespace you created to current 
3. create the secret
4. create the configmap
5. create the db-deployment
6. create the db-service 

Commands 
kubectl create namespace demo

kubectl config set-context --current --namespace=demo

kubectl create -f secret.yaml

kubectl create -f configmap.yaml

kubectl create -f db-deployment.yaml

kubectl get pods --watch

![sql_artifact](https://user-images.githubusercontent.com/87015945/152524614-981e553e-3e3e-46b8-8cda-de729877976f.png)
