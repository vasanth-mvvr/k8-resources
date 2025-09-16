# **kubernetes container orchestration**
* display nodes in k8 cluster
```
kubectl get pods
```
* version
```
kubectl version
```
*   namespace is used to build a project in isolation environment where other can't get access to it
* list all available namespaces
```
kubectl api-resources | wc -l
```
# **CLI commands for direct creating**
* To create a namespace
```
kubectl create namespace <name>
```
* To see the created namespace
```
kubectl get namespace or ns
```
* to delete namespace
```
kubectl delete namespace <name>
```
# **Creating using yaml script** 
```
kubectl apply -f <filename>
```
* To delete the yaml
```
kubectl delete -f <filename>
```
* To describe 
```
kubectl describe namespace <filename>
```
* To see the running pods
```
kubectl get pods
```
* To enter into the multi-container after running
```
kubectl exec -it multi-container -c <container-name> --bash
```
