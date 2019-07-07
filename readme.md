## Install wordpress and mysql on kube cluster with persistent volumes

#### Usage
1. git clone the repository

`git clone https://github.com/moziauddin/wpMysql-pvc-kubernetes .`

1. Run the below command to startup a cluster with wordpress and mysql

`kubectl apply -f ./`

1. Change password in the kustomization.yaml file

1. check using the below commands

```
kubectl get pods
kubectl get services
kubectl get pvc
kubectl get secret
```

1. To delete the cluster run `kubectl delete -f ./`
