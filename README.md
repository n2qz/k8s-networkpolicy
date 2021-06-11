# k8s-networkpolicy

My collection of sample Kubernetes network policies.

Use at your own risk.

Some of these are deployable as-is, and some will need to be tailored
for your use case.  You can deploy multiple polices which will have
the desired effect in combination.  For example, you might deploy
`networkpolicy-default-deny-egress.yaml`,
`networkpolicy-default-deny-ingress.yaml`, and
`networkpolicy-allow-ingress-controller-ingress.yaml` in a namespace
which should allow only inbound traffic from the ingress controller to
pods having the appropriate label.



