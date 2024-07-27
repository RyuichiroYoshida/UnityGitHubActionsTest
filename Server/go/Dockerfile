#FROM golang:1.22-alpine
FROM golang:1.22
RUN apt update
RUN apt install tree
#RUN apk update && apk add git

WORKDIR ./server
COPY ./go/main.go ./server
COPY ./go/go.mod ./server
COPY ./go/go.sum ./server

#RUN go get -u github.com/gin-gonic/gin
#RUN go get -u gorm.io/driver/mysql
#RUN go get -u gorm.io/gorm