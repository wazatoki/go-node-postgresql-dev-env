FROM golang:1.17.5-alpine3.14

WORKDIR /tmp

# sql-migrate
RUN go install -tags 'postgres' github.com/golang-migrate/migrate/v4/cmd/migrate@latest

WORKDIR /workspace
