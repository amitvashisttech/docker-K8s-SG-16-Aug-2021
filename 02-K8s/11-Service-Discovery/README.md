  ```
  480  git pull 
  481  ls
  482  cd 02-K8s/11-Service-Discovery/
  483  ls
  484  kubectl apply -f secrets.yaml 
  485  ls
  486  kubectl apply -f database.yaml 
  487  kubectl get pods 
  488  ls
  489  kubectl database-service.yml 
  490  kubectl apply -f database-service.yml 
  491  ls
  492  vim database.yaml 
  493  ls
  494  vim helloworld-app-deployment.yml 
  495  kubectl get pods,secrets,svc 
  496  kubectl apply -f helloworld-app-deployment.yml 
  497  kubectl apply -f helloworld-app-svc.yml 
  498  kubectl get pods 
  499  vim database.yaml 
  500  cat secrets.yaml 
  501  cat database-service.yml 
  502  ls
  503  vim helloworld-app-deployment.yml 
  504  vim helloworld-app-svc.yml 
  505  ls
  506  kubectl get pods 
  507  kubectl get svc 
  508  kubectl log helloworld-deployment-6d586b658d-zqj8n
  509  kubectl logs helloworld-deployment-6d586b658d-zqj8n
  510  curl -vv http://172.31.0.101:30654/
  511  kubectl get pods 
  512  kubectl exec -it helloworld-deployment-6d586b658d-f92jz -- sh 
  513  ls
  514  cd 
  515  ls
  516  kubectl run -it busybox-1 --image=busybox:1.28 --restart=Never -- sh 
  517  kubectl get pods 
  518  kubectl exec -it database -- mysql -u root -p 
  519  ls
  520  history 
  521  cd docker-K8s-SG-16-Aug-2021/02-K8s/11-Service-Discovery/
  522  ls
  523  history > README.md
```
