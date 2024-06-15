# Description
Infrastructure and configuration for monitoring of the homelab.

# Setup details
Monitoring is done using kube prometheus stack (Grafana + Prometheus + Alertmanager customized to monitor Kubernetes cluster). Deployment is done via Helm Chart, and is managed by central ArgoCD (https://github.com/mcapala-homelab/argocd).
