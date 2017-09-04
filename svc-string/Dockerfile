FROM golang:1.9

ADD . /go/src/github.com/pNagi/try-go-kit/svc-string
RUN go install github.com/pNagi/try-go-kit/svc-string

ENTRYPOINT /go/bin/svc-string
