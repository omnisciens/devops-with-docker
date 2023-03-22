FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN apt-get update
RUN apt-get -y install curl

COPY read_website.sh .
RUN chmod +x read_website.sh

CMD ./read_website.sh
