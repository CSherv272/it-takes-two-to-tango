FROM golang:latest

WORKDIR /app

ADD . ./
RUN go mod download

RUN go build -o build/program/app main.go

CMD ["/app/build/program/app"]