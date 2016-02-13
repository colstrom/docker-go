FROM colstrom/alpine

RUN apk-install \
                bash \
                git \
                perl

ADD bin pkg src /usr/lib/go

WORKDIR /build
