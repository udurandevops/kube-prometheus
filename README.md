# kube-prometheus

kubectl port-forward svc/kube-prometheus-stack-prometheus 9090:9090 -n kube-prometheus

# Grafana prometheus alert link : https://samber.github.io/awesome-prometheus-alerts/rules#kubernetes
# Grafana pod restart alert rule : increase(kube_pod_container_status_restarts_total[5m]) > 0
