This helm chart will speed up certificate creation. There are a few requirements such as cert-manager https://cert-manager.io/ and helm https://helm.sh/. Once the depencies are install you can install the chart using `helm install` command.


Requirements Installation:
Cert-manager
kubectl apply -f https://github.com/jetstack/cert-manager/releases/download/v1.7.0/cert-manager.yaml
Helm
curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash

