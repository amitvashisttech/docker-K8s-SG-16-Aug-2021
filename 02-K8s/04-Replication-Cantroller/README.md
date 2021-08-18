   ```
   86  cd K8s-docker-ericsson-2020-Dec-07/
   87  ls
   88  cd 02-Kubernetes/
   89  ls
   90  mkdir 04-Replication-Cantroller
   91  cd 04-Replication-Cantroller/
   92  ls
   93  vim helloworld-rc.yaml
   94  ls
   95  kubectl get rc 
   96  kubectl api-resources
   97  cat helloworld-rc.yaml 
   98  vim helloworld-rc.yaml 
   99  ls
  100  kubectl get rc 
  101  kubectl get pods 
  102  kubectl create -f helloworld-rc.yaml 
  103  kubectl get rc 
  104  kubectl get pods
  105  kubectl delete pod helloworld-controller-9zj6p helloworld-controller-fwcrx
  106  kubectl get pods
  107  kubectl delete pod hello-k8s mypythonwebapp                
  108  kubectl get pods
  109  kubectl get rc 
  110  kubectl scale=5 rc helloworld-controller
  111  kubectl scale replicas=5 rc helloworld-controller
  112  kubectl scale --replicas=5 rc helloworld-controller
  113  kubectl get rc 
  114  kubectl get pods
  115  kubectl scale --replicas=10 rc helloworld-controller
  116  kubectl get pods
  117  kubectl scale --replicas=1 rc helloworld-controller
  118  kubectl get pods
  119  kubectl scale --replicas=1 rc helloworld-controller
  120  kubectl get pods
  121  kubectl delete pod helloworld-controller-xgr24
  122  kubectl get pods
  123  kubectl delete -f helloworld-rc.yaml 
  124  ls
  125  history 
  126  history > README.md
  ```
