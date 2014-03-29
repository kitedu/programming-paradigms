Scala
===

## Setup

```sh
$ cd Scala
$ docker build -t scala .
$ docker run -i -t scala
```

## Usage

Run the following commands in the docker container. This example covers [this code snippet](http://www.scala-lang.org/old/node/166.html). Save the snippet as `HelloWorld.scala`. (The filename has to be the same as the classname.)

### Compile

```sh
$ scalac HelloWorld.scala
```

### Run

```sh
$ scala HelloWorld
```

### Credits
Credits to [lukasz's](https://index.docker.io/u/lukasz/docker-scala/) Scala Docker Container, on which this container is build on!
