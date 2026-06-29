Required port forwards for monitoring

- kubectl --namespace monitoring port-forward svc/grafana 3000
- kubectl --namespace monitoring port-forward svc/prometheus-k8s 9090
- kubectl port-forward svc/argocd-server -n argocd 8080:443
