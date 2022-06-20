FROM golang:1.16

WORKDIR /go/src
ENV PATH="/go/bin:${PATH}"


RUN apt-get update && \
    apt-get install build-essential Librdkafka-sev -y

CMD ["tail", "-f", "/dev/null"]