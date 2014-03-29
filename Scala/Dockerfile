FROM lukasz/docker-scala

RUN apt-get update
RUN apt-get install -y vim

RUN mkdir /code
ADD HelloWorld.scala /code/HelloWorld.scala

WORKDIR /code

CMD ["bash"]
