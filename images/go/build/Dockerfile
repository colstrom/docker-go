FROM colstrom/alpine

RUN apk-install \
                bash \
                git \
                perl

ADD src /usr/lib/go/src
ADD pkg /usr/lib/go/pkg
ADD bin /usr/lib/go/bin

WORKDIR /build
