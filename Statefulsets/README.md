# Statefulsets
StatefulSets represent a set of Pods with unique, persistent identities and stable hostnames that GKE maintains regardless of where they are scheduled. The state information and other resilient data for any given StatefulSet Pod is maintained in persistent disk storage associated with the StatefulSet.

Stateless applications tend to include containerized microservices apps, CDN, print services, or any short term workers. and are easy for both deploying and managing resources. Stateful applications typically involve some database, such as Cassandra, MongoDB, or MySQL and processes a read and/or write to it

**Note:** This tutorial assumes that your cluster is configured to dynamically provision PersistentVolumes. If your cluster is not configured to do so, you will have to manually provision two 1 GiB volumes prior to starting this tutorial.

#### To create statefusets run the below command
```
$ kubectl apply -f statefulset.yaml
```
#### To check the created service run below command
```
$ kubectl get service nginx
```
#### To check created statefulset run below command
```
$ kubectl get statefulset web
```
