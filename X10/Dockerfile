FROM ubuntu:12.04
MAINTAINER Johannes Schickling "schickling.j@gmail.com"

ENV JAVA_HOME /usr

RUN apt-get update
RUN apt-get install -y vim
RUN apt-get install -y wget default-jdk
RUN wget http://heanet.dl.sourceforge.net/project/x10/x10/2.4.2/x10-2.4.2_linux_x86_64.tgz
RUN mkdir /x10
RUN tar xvzf x10-2.4.2_linux_x86_64.tgz -C /x10
RUN rm x10-2.4.2_linux_x86_64.tgz
RUN ln -s /x10/bin/* /usr/bin/
RUN mkdir /code
ADD HelloWholeWorld.x10 /code/HelloWholeWorld.x10

WORKDIR /code

CMD ["bash"]
