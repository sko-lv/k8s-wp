# Kubernetes WordPress example project

## Prerequisites:
* [Minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/) 

### Run project
    minikube start 
    kubectl apply -f all_wp.yaml
    kubectl get deploy,rs,po,pv -o=wide
    ...
    minikube stop
