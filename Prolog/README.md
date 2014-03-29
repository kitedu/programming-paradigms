Prolog
======

## Setup

```sh
$ cd Prolog
$ docker build -t prolog .
$ docker run -i -t prolog
```

## Usage

Run the following commands in the docker container. This example covers the file `hello_world.pl`. (It's already in the `/code` directory.). The filename has to be lowercase.

### Run

```sh
$ swipl

?- [hello_world].
?- hello_world.
```
