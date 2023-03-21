# ⚙️ ansible-k8s-argo-cd-installation

## 🛠️ Technologies used
- [Ansible](https://www.ansible.com/) IT automation tool

## 🎯 Targets
- [Kubernetes Cluster](https://kubernetes.io/) Container orchestration tool

## 📃 Instructions

### Get credentials

```bash
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
```