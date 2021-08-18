``` 

  kubectl cluster-info
  kubectl api-versions
  kubectl api-resources
  kubectl proxy --address='YourMasterServerIP' --port=8001 --accept-hosts='.' --accept-paths='.' &
  
  curl http://172.31.0.10:8001/api/v1/secrets
  curl http://172.31.0.10:8001/api/v1/pods
  curl http://172.31.0.10:8001/api/v1/pods  | grep -A10 "hello-k8s"
```
