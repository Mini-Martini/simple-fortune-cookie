FROM golang:1.26.5

WORKDIR /app

COPY . .

RUN go build -o frontend-app .

EXPOSE 8080

CMD ["./frontend-app"]