# Traefik installation on kubernetes

1. create traefik namespace
```
kubectl create namespace traefik
```
2. apply all yaml file to traefik namespace
```
kubectl apply -n traefik -f .
```
