Useful Link - https://www.digitalocean.com/community/tutorials/how-to-deploy-to-kubernetes-using-argo-cd-and-gitops

argocd app create app-of-apps --repo https://github.com/ninoyr17/argocd.git --path app-of-apps --dest-server https://kubernetes.default.svc --dest-namespace default