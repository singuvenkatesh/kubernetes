## Add label to the Node

```
kubectl label nodes <your-node-name> diskType=ssd

 Labels & selctors: Kubernetes objects use labels and selectors internally to connect different objects together.
 
 Selector : To link the service to a set of pods we use selector.



 kubectl get pods -l env=dev
 kubectl get pods -l bu=finance --no-headers | wc -l
 kubectl get all -l env=prd --no-headers | wc -l
 kubectl get all --selector env=prod,bu=finance,tier=frontend
```
