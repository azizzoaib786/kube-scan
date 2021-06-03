## Kube-Scan
### Get the risk score of your workloads

https://github.com/octarinesec/kube-scan

Un-official helm chart of kube-scan.

### Deployment

`helm upgrade kube-scan . -n default --install -f values.yaml`

### Port Forwarding

`kubectl port-forward --namespace kube-scan svc/kube-scan-ui 8080:80`
