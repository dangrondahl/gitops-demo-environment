# Usage

To apply the hello-go app and its resources under this repository, run:

```bash
argocd app create hello-go --repo https://github.com/dangrondahl/gitps-demo-environment.git --path hello-go --dest-server https://kubernetes.default.svc --dest-namespace dev
```

