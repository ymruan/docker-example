From ubuntu:14.04
MAINTAINER ruan yiming "ymruan@gmail.com"
ENV REFRESHED_AT 2015-07-15

RUN apt-get update
RUN apt-get -y install redis-server redis-tools

EXPOSE 6379
ENTRYPOINT ["/usr/bin/redis-server"]
CMD []
