FROM colstrom/alpine

RUN apk-install \
                bash \
                git \
                perl

WORKDIR /usr/lib/go

COPY src src
COPY pkg pkg
COPY bin bin

WORKDIR /build
