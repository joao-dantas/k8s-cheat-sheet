`kubectl create -f replicaset-definition.yaml`

`kubectl get replicaset`

`kubectl delete replicaset myapp-replicaset`

`kubectl replace -f replicaset myapp-replicaset`

`kubectl scale -replicas=6 -f replicaset-definition.yaml`
