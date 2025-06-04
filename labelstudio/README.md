- 참조 사이트 : https://labelstud.io/guide/install_k8s

### 1. 설치

kubectl config set-context --current --namespace=labelstudio <br>

helm repo add heartex https://charts.heartex.com/ <br>
helm repo update heartex<br>

helm install labelstudio heartex/label-studio -f ls-values.yaml
