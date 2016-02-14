FROM colstrom/alpine

WORKDIR /usr/lib/go

COPY src src
COPY pkg pkg
COPY bin bin

WORKDIR /go

ENV GOPATH /go
ENV PATH ${GOPATH}/bin:/usr/lib/go/bin:${PATH}

ENTRYPOINT ["go"]
