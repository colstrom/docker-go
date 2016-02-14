FROM colstrom/alpine

RUN apk-install \
                bash \
                git \
                perl

WORKDIR /usr/lib/go

ADD src src
ADD pkg pkg
ADD bin bin

WORKDIR /build
