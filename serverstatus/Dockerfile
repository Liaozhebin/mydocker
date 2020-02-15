FROM python:2.7.17-slim-stretch
MAINTAINER liaozhebin <liaozhebin@gmail.com>
WORKDIR /root
RUN apt-get update && \
    apt install net-tools procps iproute2 wget lrzsz -y && \
    wget --no-check-certificate "https://github.com/Liaozhebin/mydocker/raw/master/serverstatus/client-linux.py" && \ 
    echo "Asia/Shanghai" > /etc/timezone && rm /etc/localtime
 CMD ["/usr/local/bin/python"]
