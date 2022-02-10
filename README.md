
```
kubectl create ns traefik-test

helm install --namespace=traefik-test \
    traefik traefik/traefik

helm upgrade traefik traefik/traefik -f traefik-values.yml -n traefik-test
```