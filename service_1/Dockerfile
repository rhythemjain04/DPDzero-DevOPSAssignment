FROM golang:1.24.4-alpine
WORKDIR /app
COPY . .
RUN go mod download
RUN go build -o service1
EXPOSE 8001
CMD ["./service1"]