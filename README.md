# My Kubernetes deployments
## Exobrain
Just a pod with an emanote container with my Zettelkasten and a `git-sync` to keep it updated

## Test
A `StatefulSet` with a `busybox` container that has enough tools to troubleshoot networking problems. There are some features I'd like to add but I don't know how:
* Pod name based on host's name. This seems impossible, but currently the situation is suboptimal. Pod `test-0` might be deployed on `worker-1`, if I want to test exactly which nodes have connectivity issues among themselves this is confusing
* Set replica number to node number so I can have one for each node. Currently I've ensured that no two pods are scheduled to the same node (following [this guide](https://medium.com/@johnjjung/building-a-kubernetes-daemonstatefulset-30ad0592d8cb)), but I'd also like to have exactly one per node.
