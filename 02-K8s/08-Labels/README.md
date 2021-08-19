
```
  374  kubectl get pods --show-labels
  378  kubectl get pods --show-labels
  382  kubectl get pods --show-labels
  527  mkdir 08-Labels
  528  cd 08-Labels/
  539  kubectl get nodes --show-labels
  540  kubectl label nodes k8s-worker-02 hardware=virtual
  541  kubectl get nodes --show-labels
  544  kubectl label nodes k8s-worker-01 hardware=virtual
  556  kubectl label nodes k8s-worker-01 hardware=virtual
  557  kubectl label nodes k8s-worker-01 env=prod
  562  kubectl delete -f 08-Labels/
  564  kubectl get nodes --show-labels
  565  kubectl label nodes k8s-worker-01 env-
  566  kubectl get nodes --show-labels
  567  kubectl label nodes k8s-worker-01 hardware-
  568  kubectl get nodes --show-labels
  569  kubectl label nodes k8s-worker-02 hardware-
  571  kubectl create -f 08-Labels/
  573  kubectl delete -f 08-Labels/
  575  cd 08-Labels/
  577  history | grep -i label
  578  history | grep -i label > README.md
```
