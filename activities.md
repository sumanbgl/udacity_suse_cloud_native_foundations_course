**7th July 2021**
docker file for packaging go application
```
FROM golang:alpine

WORKDIR /go/src/app

ADD . .

RUN go mod init #added this line to resolve error

RUN go build  -o helloworld

EXPOSE 6111

CMD ["./helloworld"]
```

```
# build the image
docker build -t go-helloworld .

docker run -d -p 6111:6111 go-helloworld

curl -X GET http://localhost:6111
 expected output: Hello World

# tag the image
docker tag go-helloworld pixelpotato/go-helloworld:v1.0.0

# push the image
docker push pixelpotato/go-helloworld:v1.0.0
```
