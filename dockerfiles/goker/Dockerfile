FROM golang:1.17

RUN apt update && apt install -y vim rsync python3 python3-pip python3-matplotlib

RUN #pip3 install pandas numpy --break-system-packages
RUN pip3 install pandas numpy

#
#ENV GO111MODULE=off
#RUN go get golang.org/x/tools/cmd/goimports
#RUN go get github.com/sasha-s/go-deadlock
#RUN go get go.uber.org/goleak
#
#RUN go get github.com/docker

#ENV PATH=/go/bin:${PATH}

WORKDIR /root/gobench
#RUN go get github.com/docker/docker/api/types@v19.03.8
#RUN go get github.com/docker/docker/api/types/container@v19.03.8
#RUN go get github.com/docker/docker/api/types/mount@v19.03.8
#RUN go get github.com/docker/docker/client@v19.03.8
#RUN go get github.com/docker/docker/pkg/stdcopy@v19.03.8
#RUN go get github.com/hashicorp/go-version
#RUN go get .
#RUN cd /root/gobench
#RUN go mod init gobench
##RUN go get -u go.uber.org/goleak
#
#RUN go get -d golang.org/x/tools/cmd/goimports
#RUN go get -d github.com/sasha-s/go-deadlock
#RUN go get -d go.uber.org/goleak
#RUN go get -d github.com/docker/docker/api/types@v19.03.8
#RUN go get -d github.com/docker/docker/api/types/container@v19.03.8
#RUN go get -d github.com/docker/docker/api/types/mount@v19.03.8
#RUN go get -d github.com/docker/docker/client@v19.03.8
#RUN go get -d github.com/docker/docker/pkg/stdcopy@v19.03.8
#RUN go get -d github.com/hashicorp/go-version
