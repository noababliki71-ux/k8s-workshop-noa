Kubernetes Workshop – Noa

Deployed:
- MySQL (StatefulSet + PVC + Secret)
- WordPress (Deployment + Service)
- Ingress with Nginx
- Monitoring stack using Helm (Prometheus + Grafana)

Verification:
- kubectl get pods -n wp
- kubectl get svc -n wp
- kubectl get ingress -n wp
