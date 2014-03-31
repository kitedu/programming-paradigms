FROM ubuntu:12.04
MAINTAINER Tim Suchanek "tim.suchanek@gmail.com"

RUN apt-get update
RUN apt-get install -y vim gcc libcr-dev mpich2 mpich2-doc
RUN mkdir /code
ADD hello.c /code/hello.c

WORKDIR /code

CMD ["bash"]
