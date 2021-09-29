

A Kubernetes volume is a directory that contains data accessible to containers in a given Pod in the orchestration and scheduling platform. Volumes provide a plug-in mechanism to connect ephemeral containers with persistent data stores elsewhere.


A persistent volume is a piece of storage in a cluster that an administrator has provisioned. It is a resource in the cluster, just as a node is a cluster resource. A persistent volume is a volume plug-in that has a lifecycle independent of any individual pod that uses the persistent volume.

A Persistent Volume Claim describes the amount and characteristics of the storage required by the pod, finds any matching persistent volumes and claims these. Storage Classes describe default volume information (filesystem,size,block size etc).
