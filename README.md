# kubedbg

A simple docker image for troubleshooting kubernetes applications.

kubedbg is a debian stable image shipped with useful tools:
- curl
- nslookup
- nmap
- kubectl

## How to use kubedbg?

Just create a pod:

```
kubectl run -i --tty my-kubedbg --image=sirot/kubedbg --restart=Never --rm --namespace=xxx
```

All PR are welcome!
