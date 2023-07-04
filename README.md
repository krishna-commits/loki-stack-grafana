# loki-stack-grafana


helm repo add grafana https://grafana.github.io/helm-charts

helm repo update

helm install loki-stack grafana/loki-stack --set grafana.rbac.pspEnabled=false --values values.yaml -n monitor



18534 (code)

