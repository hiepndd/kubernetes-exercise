FROM golang:1.12
MAINTAINER Hiep Nguyen <hiepdangnguyendai@gmail.com>
ADD main.go /go/src/github.com/kubernetes-exercise/docker/main.go
EXPOSE 8080
WORKDIR /go/src/github.com/kubernetes-exercise/docker
ENTRYPOINT [ "go","run","main.go" ]
