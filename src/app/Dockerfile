FROM golang:alpine

WORKDIR /go

COPY . .

RUN go build ./src/github.com/brtmvdl/repository_name/main.go 

CMD ./main
