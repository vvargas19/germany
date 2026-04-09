FROM golang:1.24-alpine AS builder
WORKDIR /app
COPY . .
RUN go build -o min .

FROM gcr.io/distroless/static:nonroot
WORKDIR /app
COPY --from=builder /app/main .

EXPOSE 8080
CMD ["/app/main"]
