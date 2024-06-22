FROM golang:latest
WORKDIR /app
ADD . /app/
RUN go build -o ./out/tensorpad .
EXPOSE 8000
ENTRYPOINT ["./out/tensorpad"]
