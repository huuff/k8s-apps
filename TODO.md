# Tasks
* Try to set the `--control-plane-endpoint` to `cervantes.haff.xyz`
* Try to set a load balancer for all nodes so I can point my subdomains there
* `cert-manager` in my ingress helmfile, maybe even try setting the cluster from 0 using just helmfiles
* A pod that monitors a web page to ensure it won't change
* Encrypt secrets
* A controller that removes pods after some time specified by an annotation
* Use a vertical pod autoscaler (VPA) for my apps
* Some AppArmor, SELinux, seccomp profiles (Is there a bane controller/operator? Can I make it?) (runtime/default? does containerd have one?)
* (Emanote) Should allow specifying several repositories to create a layered zettelkasten
* Some audit policy
* Disable anonymous auth
* Some network policies
* Make the postgres operator work with my kyverno policies
* (test) Allowing elevated privileges is effectively the same as running as root. Try to fix that somehow (there's a ping allowed range for sysctl?)

