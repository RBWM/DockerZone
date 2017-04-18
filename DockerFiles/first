FROM ubuntu:trusty

MAINTAINER Venky_Docker

RUN apt-get update && apt-get -y install apache2 && service apache2 start

EXPOSE 80

CMD ["ping","google.com"]