FROM golang:alpine
LABEL owner="Damie Banjoko"
WORKDIR /go/src/app
COPY . /go/src/app/
EXPOSE 6111
RUN go mod init
RUN go build -o helloworld
CMD [ "./helloworld" ]
