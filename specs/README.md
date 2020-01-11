## Observability
```bash
minikube start -p telemetry --memory 8192 --cpus 4
kubectl apply -f prometheus/
kubectl apply -f grafana/
kubectl port-forward service/grafana 3000:3000
```
