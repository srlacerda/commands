# kubernetes-commands
some kubernetes commands


1 - Get namespaces
```
kubectl get namespaces
```


2 - Get pods from a specific namespace
```
kubectl get pods -n backend
```


3 - Get pods from a specific namespace filtering string -> gringott
```
kubectl get pods -n backend | grep gringott
```


4 - Describe pod
```
kubectl -n backend describe pod/gringott-5bb957675b-9c8tj
```


5 - Logs pod - specific container (gringott)
```
kubectl -n backend logs -f gringott-5bb957675b-9c8tj gringott
```


6 - Logs pod - all-containers
```
kubectl -n backend logs -f --all-containers gringott-5bb957675b-9c8tj
```


7 - Get containers pod (NamePod, Containers)
```
kubectl get -n backend pod -o="custom-columns=NAME:.metadata.name,CONTAINERS:.spec.containers[*].name" | grep gringot
```


8 - Get containers pod (NamePod, InitContainer, Non-InitContainer)
```
kubectl get -n backend pod -o="custom-columns=NAME:.metadata.name,INIT-CONTAINERS:.spec.initContainers[*].name,CONTAINERS:.spec.containers[*].name" | grep gringot
```
