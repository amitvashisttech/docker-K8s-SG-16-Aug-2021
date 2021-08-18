# Creating out First App

## Check the health of Cluster
```
kubectl get nodes 
```

## Configure Docker Image Pull Secrets
```
kubectl create secret generic regcred --from-file=.dockerconfigjson=/root/.docker/config.json --type=kubernetes.io/dockerconfigjson

```


## Deploy Nginx App
```
kubectl apply -f hello-k8s.yaml
```

## Check the status of PODs 
```  
kubectl get pods 
kubectl describe pods hello-k8s
```

## Let's Deploy our newly built PythonWeb App.
```
kubectl run mypythonwebapp --image=amitvashist7/mypywebapp:v3 --port=8081

or 

kubectl apply -f hello-python-webapp.yaml
```
```
kubectl get pods
NAME                  READY   STATUS    RESTARTS   AGE
hello-k8s             1/1     Running   0          6m18s
hello-python-webapp   1/1     Running   0          110s
```
