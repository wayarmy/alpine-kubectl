![Build](https://travis-ci.org/wayarmy/alpine-kubectl.svg?branch=master)

# Alpine-Kubectl

> This image contain kubectl in the alpine image.

### Installation

- `docker pull wayarmy/alpine-kubectl:latest`

### Kubectl Version

- Latest: 1.8.0
- 1.6.7
- 1.7.4

### Run with kubeconfig

- `docker run -it -v $PWD/.kube:/root/.kube wayarmy/alpine-kubectl:latest kubectl --help`
