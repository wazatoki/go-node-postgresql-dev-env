FROM alpine:3.14

RUN apk add --update docker docker-compose make git && \
    mkdir /mnt/workspace && \
    mkdir /workspace

COPY work /workspace

WORKDIR /workspace
