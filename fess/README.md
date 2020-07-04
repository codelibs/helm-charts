Fess Helm Chart
------------------------

## Overview

The official Fess Helm Charts.

## Installation

### Install using the git repository

  ```
  helm install my-release ./
  ```

### KIND(Kubernetes IN Docker)

  ```
  helm install my-release -f ./kind/values.yaml ./
  ```

### Uninstall Charts

  ```
  helm uninstall my-release
  ```

## Usage

Setting up a port forward, you can now access http://localhost:8080
  
  ```
  kubectl port-forward svc/my-release-fess 8080
  ```
