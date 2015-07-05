FROM ubuntu:14.04
MAINTAINER ruan yiming "ymruan@gmail.com"
ENV REFRESH_AT 2015-07-05

RUN apt-get update
RUN apt-get -y install ruby ruby-dev build-essential redis-tools
RUN gem install --no-rdoc --no-ri sinatra json redis
RUN mdkir -p /opt/webapp

EXPOSE 4567

CMD ["opt/webapp/bin/webapp"]
