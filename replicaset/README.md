A ReplicaSet is a process that runs multiple instances of a Pod and 
keeps the specified number of Pods constant. Its purpose is to maintain the specified number of Pod instances 
running in a cluster at any given time to prevent users from losing access to their application when a Pod fails or is inaccessible.

Replication controller is the older technology that is being replaced by replicas set up, like I said,
is the new recommended way to set up replication.

The major difference difference between a replication controller and replica set is that the rolling-update command works with Replication Controllers, 
but won't work with a Replica Set. 
This is because Replica Sets are meant to be used as the backend for Deployments.
