The repository hosts Helm Charts for my Argo CD example.

# Usage

Helm must be installed to use the charts. Please refer to Helm’s documentation to get started.

Once Helm is set up properly, add the repo as follows:

```
helm repo add mapspiral https://mapspiral.github.io/example-argocd-charts
```

If you had already added this repo earlier, run helm repo update to retrieve the latest versions of the packages.

You can then run `helm search repo mapspiral` to see the charts.

# Charts

| Name               | Description                          |
| ------------------ | ------------------------------------ |
| [argocd](./argocd) | Installs Argo CD with customizations |

# Resources

[Provision a free Helm Chart repository](https://medium.com/@gerkElznik/provision-a-free-personal-helm-chart-repo-using-github-583b668d9ba4)