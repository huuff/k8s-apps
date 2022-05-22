# Tasks
* Try to set the `--control-plane-endpoint` to `cervantes.haff.xyz`
* Try to set a load balancer for all nodes so I can point my subdomains there
* `cert-manager` in my ingress helmfile, maybe even try setting the cluster from 0 using just helmfiles
* A pod that monitors a web page to ensure it won't change
* A controller that removes pods after some time specified by an annotation
* Use a vertical pod autoscaler (VPA) for my apps
* Some AppArmor profiles... is there a `bane` controller?
* (Emanote) Should allow specifying several repositories to create a layered zettelkasten
* Some audit policy
* Some network policies
* Make the postgres operator work with my kyverno policies
* A krew plugin that allows deploying a `pgcli` connection to a Zalando's postgres deployment?
* (gotify) mysql?
* Some way of checking image signatures to prevent supply chain attacks?
* Gotify reporting:
  * `falco` reporting
  * `trivy` reporting
  * Reporting on failing kyverno policies?
* Install glusterfs
* Test all of my apps with my kyverno policies because it seems some might be wrong
