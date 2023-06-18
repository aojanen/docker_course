FROM golang:1.16

WORKDIR /usr/src/app/

COPY ./example-backend ./

EXPOSE 8686

RUN go build

RUN go test ./...

ENV PORT=8686
ENV REQUEST_ORIGIN=http://127.0.0.1

#RUN ./server

