FROM debian:wheezy

MAINTAINER Shuichi Ohsawa <ohsawa0515@gmail.com>
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]
