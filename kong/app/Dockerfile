FROM golang:latest
WORKDIR /app

COPY . .

RUN go get -d -v ./...

EXPOSE 8080
CMD ["go", "run", "main.go"]