# Tasks
* Try to set the `--control-plane-endpoint` to `cervantes.haff.xyz`
* Try to set a load balancer for all nodes so I can point my subdomains there
* `cert-manager` in my ingress helmfile, maybe even try setting the cluster from 0 using just helmfiles
* A pod that monitors a web page to ensure it won't change
* Encrypt secrets
* A controller that removes pods after some time specified by an annotation
* Use a vertical pod autoscaler (VPA) for my apps
* Some AppArmor, SELinux, seccomp profiles (Is there a bane controller/operator? Can I make it?) (runtime/default? does containerd have one?)
* LSM profiles:
  * Seccomp (runtime/default? drop all capabilities?)
  * AppArmor (bane? a bane controller?)
  * SELinux (no idea)
* (Emanote) Should allow specifying several repositories to create a layered zettelkasten
* Some audit policy
* Disable anonymous auth
* Some network policies
* Make the postgres operator work with my kyverno policies
* (test) Allowing elevated privileges is effectively the same as running as root. Try to fix that somehow (there's a ping allowed range for sysctl?)
* A krew plugin that allows deploying a `pgcli` connection to a Zalando's postgres deployment?
* (gotify) mysql?
* The anchore controller seems unmaintained... what about the trivy operator?
* More kyverno policies:
  * No `hostPID`, no `hostNetwork` and no `hostIPC`
  * No privileged containers
* Some way of checking image signatures to prevent supply chain attacks?
* Setup falco?
