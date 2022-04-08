# cpp-opencv-things

## Description

This is my first project with OpenCV, and my first project in C++ and my biggest too.

Its purpose is to generate, animate and create an image or a video only using points generated by calculus and algorithms.

## Structure

- [`includes`](includes) Contains includes included in every C++ file.
- [`dataclass`](dataclass) Contains classes definition for `Point`, `Array` and `Data`.
- [`algorithm`](algorithm) Contains various algorithms to generate arrays of points.
- [`build`](build) Contains the CMake files and the executables.

## Build

To build the project, you must have CMake, a C++ compiler and OpenCV installed.

Then run the following command in the root folder:

```
./make
```

It creates the cmake configuration files in `build/` then build the project.

The produced executables are put in `build/`:
- [`main.cpp`](main.cpp) -> `build/project`
