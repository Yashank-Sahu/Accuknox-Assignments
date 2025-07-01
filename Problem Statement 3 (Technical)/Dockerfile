# syntax=docker/dockerfile:1
FROM golang:1.24.4-alpine

WORKDIR /app
COPY . .

RUN go build -o main .
EXPOSE 8080

CMD ["./main"]
