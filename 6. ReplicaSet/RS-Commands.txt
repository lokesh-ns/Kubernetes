ReplicaSet has a ability to support Equity based selectors (=, !=) and Set based selectors (In, NotIn)


# To get the ReplicaSet
kubectl get rs

# To get pods of ReplicaSet
kubectl get pods

# To get the details of ReplicaSet
kubectl describe rs <rs_name>

# To get the details of ReplicaSet pods
kubectl describe pod <rs_pod_name>

# To get the labels of ReplicaSet
kubectl get rs --show-labels

# To get the labels of ReplicaSet pod
kubectl get pod --show-labels

# To scale up the pods of ReplicaSet
kubectl scale rs <rs_name> --replicas=<number>

# To scale down the pods of ReplicaSet
kubectl scale rs <rs_name> --replicas=<number>

# To delete the pod of ReplicaSet
kubectl delete pod <rs_pod_name>