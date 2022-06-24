## Installation
The startup script running on the right will:

1. **Check Kubernetes is up and running**.
2. **Install Knative Serving with Contour as the default networking layer**.
3. **Install the Knative `kn` CLI**.
4. **Assign the variable `$externalIP` with the external IP of your Kubernetes cluster**.

> Once you see a prompt, you can click on the command below,
> it will be copied and run for you in the terminal on the right.
> This command will show you general information about your cluster.

`kubectl cluster-info`{{execute}}

**Example output:**

```sh
Kubernetes master is running at https://172.17.0.14:6443
KubeDNS is running at https://172.17.0.14:6443/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy

To further debug and diagnose cluster problems, use 'kubectl cluster-info dump'.
```

