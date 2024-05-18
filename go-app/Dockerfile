FROM golang:1.16-alpine
WORKDIR /app
COPY go.mod go.sum ./
COPY . .
RUN go mod download
CMD ["/app","go", "run","main.go"]

