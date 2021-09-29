# Kubernetes Service Objects
- In kubernetes service is an object that is logically mapped to pods based on labels.
- Firstly we have  NodePort were the service makes an internal POD accessible on a Port on the Node.
- The second is cluster IP And in this case the service creates a virtual IP inside the cluster to enable communication between different services such as a set of front end servers to a set of back end servers.
- The third type is a LoadBalancer, were it provisions a load balancer for our service in supported cloud providers.
- Service can be single point of contact like loadbalancer for set of pods.
- By default Pod is not expose to the internet or outside of the cluster, by using service Pod is exposed to internet.
- Any Pod create in future is added to service dynamicaly if pod label is matching with Service lable selector.  

![service](https://github.com/javahometech/kubernetes/blob/master/images/service.png)
