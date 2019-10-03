# EFK Stack on Kubernetes

My environment uses 4 CPU cores and 8GB of RAM per node.
* 1 master nodes.
* 2 worker nodes.
* 200GB volume attached to worker nodes as a Persistent Volume.

You can use your kubernetes environment. I would suggest you use 4 CPUs and 8GB of RAM per node with 1 Master and 2 Worker or more.

Run these manifests one by one.
```
kubectl create -f [manifest-name].yaml
```

To access kibana use `http://ip-master-node:30050`
