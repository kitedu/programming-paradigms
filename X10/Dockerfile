FROM ubuntu:12.04

RUN apt-get update
RUN apt-get install -y vim
RUN apt-get install -y wget default-jdk
RUN wget http://heanet.dl.sourceforge.net/project/x10/x10/2.4.2/x10-2.4.2_linux_x86_64.tgz
RUN mkdir /x10
RUN tar xvzf x10-2.4.2_linux_x86_64.tgz -C /x10
RUN ln -s /x10/bin/* /usr/bin/

ENV JAVA_HOME /usr
