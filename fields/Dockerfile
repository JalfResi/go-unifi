FROM golang:buster

WORKDIR /go/src/app
COPY . .

RUN apt-get update
RUN apt-get -y install jq unzip

CMD ["bash", "getjson.sh", "5.14.23"]
