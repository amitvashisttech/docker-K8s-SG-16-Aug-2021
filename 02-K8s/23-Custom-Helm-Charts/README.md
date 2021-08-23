```
976  mkdir 22-Custom-Helm-Chart
  977  cd 22-Custom-Helm-Chart/
  978  ls
  979  helm create mychart
  980  helm create my-python-web-app
  981  ls
  982  cd mychart/
  983  ls
  984  cat Chart.yaml
  985  cd charts/
  986  ls
  987  cd ..
  988  ls
  989  ls -R templates/
  990  cat templates/deployment.yaml
  991  ls
  992  vim values.yaml
  993  ls
  994  cd ..
  995  ls
  996  vim mychart/templates/service.yaml
  997  helm install my-nginx mychart --dry-run
  998  helm install my-nginx mychart
  999  helm list
 1000  kubectl get pods
 1001  kubectl get svc
 1002  ls
 1003  cd my-python-web-app/
 1004  ls
 1005  vim values.yaml
 1006  vim templates/deployment.yaml
 1007  vim values.yaml
 1008  ls
 1009  cd ..
 1010  ls
 1011  helm install my-python-app my-python-web-app --dry-run
 1012  helm install my-python-app my-python-web-app
 1013  kubectl get pods
 1014  kubectl get svc
```
