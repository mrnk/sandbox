FROM debian:wheezy

MAINTAINER Kentaro Morone
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]
