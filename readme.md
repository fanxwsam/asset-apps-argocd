kubectl create ns argocd
kubectl apply -n argocd -f /argocd-installation/install.yaml
kubectl apply -f /applications/argocd-ingress.yaml

kubectl get secret argocd-initial-admin-secret -n argocd -o yaml
[Text.encoding]::Utf8.GetString([Convert]::FromBase64String('MDhhUGhoOWl4cjkzOG9Paw=='))
Argo CD password: 08aPhh9ixr938oOk

<!-- cd C:\assets\srcs\real\asset-microservice-deployment\dep-manually\bootstrap\prom-graf-loki-tempo
kubectl apply -k ./deployment -n asset -->
