Elasticsearch Helm Chart
------------------------

## Overview

Elasticsearch for Fess uses [Chart](https://github.com/elastic/helm-charts/tree/master/elasticsearch) provided by Elastic.


## Instalation

### Add Helm Repository

```
helm repo add elastic https://helm.elastic.co
```

### Install Charts

```
helm install elasticsearch-master elastic/elasticsearch -f master.yaml 
helm install elasticsearch-data elastic/elasticsearch -f data.yaml 
helm install elasticsearch-client elastic/elasticsearch -f client.yaml 
```

### Uninstall Charts

```
helm uninstall elasticsearch-client
helm uninstall elasticsearch-data
helm uninstall elasticsearch-master
```
