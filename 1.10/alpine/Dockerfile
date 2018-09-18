FROM golang:1.10-alpine

LABEL maintainer "fabiorphp@gmail.com"
LABEL maintainer "philipp@haussleiter.de"

RUN apk update \
    && apk add curl \
    && curl https://glide.sh/get | sh
