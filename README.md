# nginx-helm-repo
Helm chart repository provided by SOOAH

  helm repo add nginx-helm-repo https://sooah-0208.github.io/nginx-helm-repo/index.yaml
  helm repo list
  helm repo update
  helm search repo mynginx
  helm install webserver nginx-helm-repo/mynginx
