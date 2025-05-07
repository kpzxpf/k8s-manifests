k8s-manifests

This repository contains Kubernetes manifests for the Robo-Advisor platform. It is used to manage deployments and services via GitOps with Argo CD.

Structure





auth-service/: Manifests for the authentication service.

Setup





Clone the repository: git clone https://github.com/kpzxpf/k8s-manifests.git



Apply manifests: kubectl apply -f auth-service/



Configure Argo CD as described in argocd-application.yaml.

Next Steps

Add manifests for other services (e.g., User Service) as development progresses.
