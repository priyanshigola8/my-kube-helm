helm create "helm-name"

helm install "chart-name" "helm-name" "path"

helm upgrade "chart-name" "helm-name" "path"

helm uninstall "chart-name"


helm install "chart-name" "helm-name" "path" -n "namespace-name"

helm upgrade "chart-name" "helm-name" "path" -n "namespace-name"

helm uninstall "chart-name" -n "namespace-name"
