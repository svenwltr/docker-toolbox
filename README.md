# docker-toolbox

A basic Fedora installation with tools for daily use.

## Contains

* kubectl
* netcat
* dig

## Usage

### Kubernetes

```bash
kubectl run --rm -it toolbox --image=svenwltr/toolbox /bin/bash
```

### Docker

```bash
docker run --rm -it svenwltr/toolbox /bin/bash
```
