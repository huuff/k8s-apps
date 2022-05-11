# Tasks
* Try to set the `--control-plane-endpoint` to `cervantes.haff.xyz`
* Try to set a load balancer for all nodes so I can point my subdomains there
* `cert-manager` in my ingress helmfile, maybe even try setting the cluster from 0 using just helmfiles
* `emanote`: No new privileges
* Don't mount serviceaccounts!
* A pod that monitors a web page to ensure it won't change
* An ingress for `keys`
* Good, sample Kyverno policies for:
  * Not mounting serviceaccounts
  * Not running as root
  * Not allowing privilege escalation
  * Making root file system read-only
