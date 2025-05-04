# argocd-manifest-cabana

Argocd manifest files for deploying cabana website application. Would auto update the build number from CI pipeline
Would auto trigger build with any changes made to application which gets pushed

```bash
kubectl create secret docker-registry ecr-secrets \
--docker-server=598189530267.dkr.ecr.ap-south-1.amazonaws.com \
--docker-username=AWS \
--docker-password=$(aws ecr get-login-password --region ap-south-1) \
--docker-email=pumej@yahoo.com -n default
```
