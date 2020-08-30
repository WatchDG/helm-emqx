# helm-emqx

## render
```shell script
helm template helm-emqx > emqx.yml
```

## port-forward
```shell script
kubectl port-forward --namespace emqx svc/emqx 1883 8083
```