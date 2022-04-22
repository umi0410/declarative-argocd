```console
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d

argocd login localhost:8080 --insecure

export ADMIN_PASSWORD={{CURRENT_ADMIN_PASSWORD}}

argocd account update-password --account jinsu-team-user --current-password $ADMIN_PASSWORD --new-password 123123123

argocd account update-password --account jinhee-team-user --current-password $ADMIN_PASSWORD --new-password 123123123
```