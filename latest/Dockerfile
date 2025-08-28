FROM cgr.dev/chainguard/wolfi-base:latest

LABEL maintainer="Winnie The Pooh winsdominoes@winscloud.net"

RUN apk -U upgrade \
    && chown -R nonroot:nonroot /app/ \
    && apk add caddy \
    && rm -rf /var/cache/apk/*
