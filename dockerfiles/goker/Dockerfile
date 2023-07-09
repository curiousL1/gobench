FROM golang:1.19

RUN apt update && apt install -y vim rsync python3 python3-pip python3-matplotlib

RUN pip3 install pandas numpy --break-system-packages

RUN go mod init gobench

RUN rm $GOPATH/go.mod

ENV PATH=/go/bin:${PATH}

WORKDIR /root/gobench