X10
===

## Setup

```sh
$ cd X10
$ docker build -t x10 .
$ docker run -i -t x10
```

## Usage

Run the following commands in the docker container. This example covers the file `HelloWholeWorld.x10`. (It's already in the `/code` directory.) The filename has to be the same as the classname.

### Compile

```sh
$ x10c HelloWholeWorld.x10
```

### Run

```sh
$ x10 HelloWholeWorld
```
