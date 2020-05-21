FROM alpine:latest

COPY ./scripts/daily/* /etc/periodic/daily

RUN apk update && \
apk upgrade && \
apk add --no-cache mariadb-client && \
apk add gzip && \
apk add bash && \
chmod a+x /etc/periodic/daily/*
