FROM ubuntu:14.04
MAINTAINER Ruan Yiming "ymruan@gmail.com"
ENV REFRESH_AT 2015-07-05
RUN apt-get update
RUN apt-get -y -q install nginx
RUN mkdir -p /var/www/html
ADD nigix/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/nginx.conf
EXPOSE 80

