FROM golang: 1.15

WORKDIR /GO/src/hello

COPY .  .

RUN go get -d -v ./...

RUN go install -v ./...  

CMD ("Hello")