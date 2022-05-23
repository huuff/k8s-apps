# Tasks
* Try to set the `--control-plane-endpoint` to `cervantes.haff.xyz`
* Try to set a load balancer for all nodes so I can point my subdomains there. UPDATE: Actually just use a hetzner LB for my ingress-nginx
* `cert-manager` in my ingress helmfile, maybe even try setting the cluster from 0 using just helmfiles
* A controller that removes pods after some time specified by an annotation
* Some AppArmor profiles... is there a `bane` controller?
* (Emanote) Should allow specifying several repositories to create a layered zettelkasten
* Some audit policy
* Some network policies. UPDATE: Mostly done, I'm just missing some way to connect gotify to the DB
* Make the postgres operator work with my kyverno policies
* A krew plugin that allows deploying a `pgcli` connection to a Zalando's postgres deployment?
* Gotify:
  * mysql?
  * ingress
* Some way of checking image signatures to prevent supply chain attacks?
* Gotify reporting:
  * `falco` reporting
  * `trivy` reporting
  * Reporting on failing kyverno policies?
* Install glusterfs
* Use Apprise instead of gotify
* Nicer kyverno annotations
* Set my VPAs as default resources
* Use version labels
* Clean up `values.yaml`?
