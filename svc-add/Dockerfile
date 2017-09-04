FROM golang:1.9

ADD . /go/src/github.com/pNagi/try-go-kit/svc-add
RUN go install github.com/pNagi/try-go-kit/svc-add

ENTRYPOINT /go/bin/svc-add
