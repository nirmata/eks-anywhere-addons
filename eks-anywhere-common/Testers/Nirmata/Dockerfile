FROM alpine:3.18.3

RUN apk update \
 && apk add curl jq bash

RUN curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.28.0/bin/linux/amd64/kubectl \
 && chmod +x ./kubectl \
 && mv ./kubectl /usr/local/bin
 