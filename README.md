# CLI

- Stop all the nginx pods in k8s, you can scale the deployment down to zero replicas with this command:\
  `kubectl scale deployment <pod_name> --namespace=<namespace_name> --replicas=0`