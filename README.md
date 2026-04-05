# K3s Deployment YAMLs 
### (app-of-apps ArgoCD pattern)
#### After ArgoCD is installed, clone the repo and apply the root app:
```
git clone https://github.com/DallasFormulaRacing/k3s.git
cd k3s
kubectl apply -n argocd -f root-app.yaml
```