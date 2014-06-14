CMake Deployer
==============

Easy deploy a new CMake-based build system for C++.

Usage:

```
$ git clone https://github.com/mgoral/cmake-deployer myproject

$ cd myproject

$ ./configure
Project name (all lower cases): 
myproject
Project author: 
Bob Alice

$ rm -f ./configure

$ git init
```

Now the project is ready. You can add sources, submodules (e.g. for tests, like Google Test) and
compile it (see Makefile for details):

```
$ make

$ make run

$ make run/gdb

$ make ut

$ make ut/gdb
```
