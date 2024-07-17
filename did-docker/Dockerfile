FROM --platform=linux/amd64 golang:1.22
WORKDIR /usr/src/app
COPY go.mod ./
COPY . .
RUN go build -v -o /usr/local/bin/app ./...
CMD ["app"]