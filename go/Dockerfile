ARG GO_VERSION=latest
FROM golang:${GO_VERSION}

LABEL maintainer="Marcus Yano <m.yano@dropseed.co.jp>"

#WORKDIR /go/src
WORKDIR /go/src

#ADD . /go/src
#ADD ${APP_CODE_PATH_HOST} .

RUN ls -alv && \
    pwd

#RUN go run main.go
#CMD ["go", "run", "main.go"]

EXPOSE 8080
