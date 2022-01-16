FROM alpine:3.14

RUN apk add --update docker docker-compose make git && \
    mkdir /mnt/workspace && \
    mkdir -p /workspace/golang && \
    mkdir -p /workspace/node

COPY work /workspace

WORKDIR /workspace
