FROM golang:1.14 AS builder

WORKDIR /usr/src/app

COPY . .

RUN CGO_ENABLED=0 GOOS=linux go build -a -o out .

FROM alpine

WORKDIR /usr/local/bin

COPY --from=builder /usr/src/app/ .
CMD ["./out"]
