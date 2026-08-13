FROM golang:1.26.5

WORKDIR /app

COPY . .

RUN go build -o backend-app .

EXPOSE 9000

CMD ["./backend-app"]