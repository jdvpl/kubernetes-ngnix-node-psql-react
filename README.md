# Multicontainer application

### pasos aplicar las configuraciones

```
kubectl apply -f k8s
```

### mostrar containers
```
  kubectl get pods
```

### mostrar services

```
  kubectl get services
```

### crear password para psql

```
kubectl create secret generic pgpassword --from-lteral PGPASSWORD=kakaroto
```

### ver secrets 

```
kubectl get secrets
```

### instalar controlador de nginx

```
  kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.1.1/deploy/static/provider/cloud/deploy.yaml
```

### Saber estado del driver

```
  kubectl get pods -n ingress-nginx
```
