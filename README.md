# kubedbg

A simple docker image for kubernetes applications troubleshooting.

kubedbg is a debian stable image shipped with useful tools:
- curl
- nslookup
- nmap
- traceroute
- tcpdump
- kubectl

## How to use kubedbg?

Just create a pod:

```
kubectl run -i --tty my-kubedbg --image=jcsirot/kubedbg --restart=Never --rm --namespace=xxx
```

All PR are welcome!
