# docker-toolbox

A basic Fedora installation with tools for daily use.

## Contains

* dig
* kubectl
* mtr
* netcat
* screen
* watch

## Usage

### Kubernetes

```bash
kubectl run --rm -it toolbox --image=svenwltr/toolbox /bin/bash
```

### Docker

```bash
docker run --rm -it svenwltr/toolbox /bin/bash
```
