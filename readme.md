kubectl create ns argocd
kubectl apply -n argocd -f ./argocd-installation/install.yaml
kubectl apply -f ./argocd-installation/argocd-ingress.yaml

kubectl get secret argocd-initial-admin-secret -n argocd -o yaml
[Text.encoding]::Utf8.GetString([Convert]::FromBase64String('MDhhUGhoOWl4cjkzOG9Paw=='))
Argo CD password: ulSoG6OXpqA0AVN9

<!-- cd C:\assets\srcs\real\asset-microservice-deployment\dep-manually\bootstrap\prom-graf-loki-tempo
kubectl apply -k ./deployment -n asset -->

[Text.encoding]::Utf8.GetString([Convert]::FromBase64String('WDRXcjNzS1l1SThPaXZTeA=='))
