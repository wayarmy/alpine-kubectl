![Build](https://travis-ci.org/wayarmy/alpine-kubectl.svg?branch=master)

# Alpine-Kubectl

> This image contain kubectl in the alpine image.

### Installation

- `docker pull wayarmy/alpine-kubectl:latest`

### Kubectl Version

- Support latest version of kubectl, at this time: 1.8.3

### Run with kubeconfig

- `docker run -it -v $PWD/.kube:/root/.kube wayarmy/alpine-kubectl:latest kubectl --help`
