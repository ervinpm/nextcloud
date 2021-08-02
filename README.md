# Next Cloud Kubernetes configuration

## How to use

1. This configuration assumes that dynamic nfs subdirectory is already in place

```sh
$ kubectl apply -f pvc.yaml
```

2. This configuration assumes that cert manager is already installed

```sh
$ kubectl apply -f certificate.yaml
```

3. Apply deployment

```sh
$ kubectl apply -f deployment.yaml
```

4. Apply service

```sh
$ kubectl apply -f service.yaml
```

5. Apply ingress

```sh
$ kubectl apply -f ingress.yaml
```
