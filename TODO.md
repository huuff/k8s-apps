# Tasks
* Try to set the `--control-plane-endpoint` to `cervantes.haff.xyz`
* Try to set a load balancer for all nodes so I can point my subdomains there
* `cert-manager` in my ingress helmfile, maybe even try setting the cluster from 0 using just helmfiles
* A pod that monitors a web page to ensure it won't change
* A controller that removes pods after some time specified by an annotation
* Use a vertical pod autoscaler (VPA) for my apps
* LSM profiles:
  * AppArmor (bane? a bane controller?)
* (Emanote) Should allow specifying several repositories to create a layered zettelkasten
* Some audit policy
* Some network policies
* Make the postgres operator work with my kyverno policies
* A krew plugin that allows deploying a `pgcli` connection to a Zalando's postgres deployment?
* (gotify) mysql?
* The anchore controller seems unmaintained... what about the trivy operator?
* Some way of checking image signatures to prevent supply chain attacks?
* `kube-bench` and `kube-hunter` shouldn't notify when there's nothing to notify
* Some way of notifying falco issues through gotify
* Kyverno policy to check that containers have a seccomp profile
