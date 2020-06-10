# Fess Helm Charts

The official Fess Helm Charts repository.

## Getting started

### Requirements

* Helm >=3.0.0
* Kubernetes >=1.8

### Install Charts

#### Install using Helm repository

TODO.

#### Install using the git repository

  ```
  git clone git@github.com:codelibs/helm-charts.git
  helm install fess ./helm-charts/
  ```

### Usage

Setting up a port forward, you can now access http://localhost:8080 :tada:!
```
kubectl port-forward svc/fess 8080
```

### Uninstall Charts

  ```
  helm uninstall fess
  ```

### Delete Persistent Volumes

  ```
  kubectl delete pvc -l app=fess-es
  ```

## License

[Apache License 2.0](LICENSE)
