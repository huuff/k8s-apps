# Tasks
* Try to set the `--control-plane-endpoint` to `cervantes.haff.xyz`
* Try to set a load balancer for all nodes so I can point my subdomains there
* `cert-manager` in my ingress helmfile, maybe even try setting the cluster from 0 using just helmfiles
* A pod that monitors a web page to ensure it won't change
* Good, sample Kyverno policies for:
  * Not allowing privilege escalation
  * Making root file system read-only
  * Force to specify requests and limits
  * Force to use `AlwaysPullImages`
  * (Helm chart) Set a list of namespaces on which to apply policies
  * (Helm chart) Allow enabling or disabling specific policies
* Encrypt secrets
* A controller that removes pods after some time specified by a label
* Use a vertical pod autoscaler (VPA) for my apps
