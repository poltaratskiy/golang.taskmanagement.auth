FROM golang:1.17.8

COPY . /app
WORKDIR /app

RUN go build -v -o /app/bin

EXPOSE 8080

ENTRYPOINT [ "/app/bin" ]