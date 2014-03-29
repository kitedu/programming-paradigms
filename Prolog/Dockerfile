FROM ubuntu:12.04
MAINTAINER Johannes Schickling "schickling.j@gmail.com"

RUN apt-get update
RUN apt-get install -y vim
RUN apt-get install -y swi-prolog
RUN mkdir /code
ADD hello_world.pl /code/hello_world.pl

WORKDIR /code

CMD ["bash"]
