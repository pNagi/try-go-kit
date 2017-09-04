FROM golang:1.9

ENV ADD_API_HOST localhost
ENV STR_API_HOST localhost
ENV ADD_API_PORT 8081
ENV STR_API_PORT 8080

ADD . /go/src/github.com/pNagi/try-go-kit/gateway
RUN go install github.com/pNagi/try-go-kit/gateway

ENTRYPOINT /go/bin/gateway
