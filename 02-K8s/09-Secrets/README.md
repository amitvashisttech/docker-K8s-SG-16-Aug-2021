```
312  kubectl get secrets
  313  kubectl get pods
  314  kubectl get secrets
  315  echo  -n "AmitVashist" > /root/username.txt
  316  echo  -n "Pass@word123" > /root/password.txt
  317  cat /root/username.txt
  318  cat /root/password.txt
  319  kubectl create secret generic mysecrets --from-file=/root/username.txt --form-file=/root/password.txt
  320  kubectl create secret generic mysecrets --from-file=/root/username.txt --from-file=/root/password.txt
  321  kubectl get secrets
  322  kubectl describe secrets mysecrets
  323  kubectl edit secrets mysecrets
  324  ls
  325  cd 02-Kubernetes/
  326  ls
  327  cd 09-Secrets/
  328*
  329  cat helloworld-secrets.yaml
  330  vim helloworld-secrets.yaml
  331  ls
  332  kubectl apply -f helloworld-secrets.yaml
  333  kubectl get secrets
  334  kubectl describe secrets mysecrets
  335  kubectl describe secrets my-db-secrets
  336  kubectl get secrets my-db-secrets
  337  kubectl get secrets my-db-secrets -o yaml
  338  kubectl get secrets my-db-secrets -o json
  339  kubectl get secrets my-db-secrets -o yaml
  340  ls
  341  vim helloworld-secrets-volumes.yaml
  342  kubectl apply -f helloworld-secrets-volumes.yaml
  343  vim helloworld-secrets-volumes.yaml
  344  kubectl apply -f helloworld-secrets-volumes.yaml
  345  kubectl get pods
  346  kubectl describe pod helloworld-deployment-64968b454c-9mtmk
  347  kubectl get pods
  348  kubectl exec -it helloworld-deployment-64968b454c-9mtmk -- bash
  349  kubectl exec -it helloworld-deployment-64968b454c-9mtmk -- /bin/sh
  350  ls
  351  kubectl delete -f helloworld-secrets-volumes.yaml
  352  cd ..
  353  ls
  354  kubectl delete -f 09-Secrets/
```
