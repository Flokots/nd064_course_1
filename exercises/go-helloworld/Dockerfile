FROM golang:alpine
LABEL maintainer="Florence Kotohoyoh"

WORKDIR /go/src/app
ADD . .
RUN go mod init && go build -o helloworld

EXPOSE 6111

CMD ["./helloworld"]
