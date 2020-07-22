FROM golang:1.12-alpine as builder

#RUN apk add --no-cache

WORKDIR /go/src/cer
COPY ./cer.go .
RUN go build cer.go

FROM scratch

COPY --from=builder /go/src/cer/cer .
ENTRYPOINT ["./cer"]