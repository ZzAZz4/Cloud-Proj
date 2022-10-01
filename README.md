# Cloud-Proj

Aplicación de recomendaciones utilizando machine learning y kubernetes.

## Deployment

```
kubectl apply -f kubernetes\django-deployment.yaml
kubectl apply -f kubernetes\django-svc.yaml
kubectl get svc django
```

Si esta usando minikube como cluster, puede utilizar el siguiente comando para conseguir el url:

```
minikube service django
```
