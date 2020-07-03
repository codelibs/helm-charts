# Fess Helm Charts

The official Fess Helm Charts repository.

## Getting started

### Requirements

* Helm >=2.0.0
* Kubernetes >=1.8

### Install Charts

#### Install using Helm repository

TODO.

#### Install using the git repository

  ```
  git clone git@github.com:codelibs/helm-charts.git
  helm install my-release ./helm-charts/
  ```

#### KIND(Kubernetes IN Docker)

  ```
  git clone git@github.com:codelibs/helm-charts.git
  helm install my-release -f ./helm-charts/kind/values.yaml ./helm-charts/
  ```

### Usage

Setting up a port forward, you can now access http://localhost:8080 :tada:
  
  ```
  kubectl port-forward svc/my-release-fess 8080
  ```

### Uninstall Charts

  ```
  helm uninstall my-release
  ```

## License

[Apache License 2.0](LICENSE)
