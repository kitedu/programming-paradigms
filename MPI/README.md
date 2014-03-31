MPI
===
## Caution: This is still being tested and is dicussed at
[stackoverflow](http://stackoverflow.com/questions/22736336/mpi-on-ubuntu-hello-world-segmentation-fault)
## Setup

```sh
$ cd MPI
$ docker build -t mpi .
$ docker run -i -t mpi
```

## Usage

Run the following commands in the docker container. This example covers [this code snippet](http://condor.cc.ku.edu/~grobe/docs/intro-MPI-C.shtml). It's already in the /code directory of the Docker Container. (The filename has to be the same as the classname.)

### Compile

```sh
$ mpicc hello.c -o hello
```

### Run

```sh
$ mpirun -np 4 hello
```
