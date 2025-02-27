# Particle

## Description

This is a simple header only library for particle simulation.

## Folder structure

- examples: currently with only one example of how to use the library with MPS method (see S. Koshizuka and Y. Oka, "Moving particle semi-implicit method for fragmentation of incompressible fluid," Nuclear Science and Engineering, Vol 123, pp. 421–434, 1996).
- libs: unit tests for each sub-module of the library.
- particle: library header files.
- src: benchmark executables.

## Building

We use CMake for build automation. We also use a few libraries that must be installed:
- Boost
- Cuda
- VTK

With those dependencies installed you should be able to compile the library with a simple:
```
$ mkdir build
$ cd build
$ cmake ..
```
Latest test on a Debian 10 (buster), Boost 1.67, Cuda 11.4.2, VTK 7.1, gcc 8.3.0.
