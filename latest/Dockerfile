FROM cgr.dev/chainguard/nginx:latest

LABEL maintainer="Winnie The Pooh winsdominoes@winscloud.net"

RUN apk -U upgrade \
    && apk add caddy \
    && rm -rf /var/cache/apk/*
