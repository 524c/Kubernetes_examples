## Install httpbin

```
kubectl apply -f httpbin.yaml

## port forward
kubectl port-forward svc/httpbin 8080:8080

## httpbin online help
https://httpbin.org/

## test
curl http://localhost:8080/headers
curl http://localhost:8080/ip
curl http://localhost:8080/user-agent
```
