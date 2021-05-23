# HashCode 2018

## Introduction

My solution for the Google Hash Code 2018 qualification round problem. It consisted in the multi-vehicle pickup and delivery problem with time windows.

## Statement

You can check the problem statement [here](statement.pdf).

## Usage
The code does not have any dependencies, it only uses the standard Java libraries. Runs on Java 8 and newer versions.

It can be built with `java` and `javac` commands or using the Makefile provided (which only wraps these commands).

Build the soures with:
```
javac src/*/*.java
```
or
```
make
```

To run the code:
```
java src.simulation.Main
```
or
```
make run
```

To clean the build files:
```
rm src/*/*.class
```
or
```
make clean
```

## Scores
The points scored with this solution are:

| Data set | Points    |
|----------|-----------|
| a        |4          |
| b        |176.895    |
| c        |14.994.551 |
| d        |7.687.306  |
| e        |21.460.514 |
| Total    |44.319.270 |

The maximum score obtained in this problem was 49.776.211 points.

## License
This code is licensed under [Apache License 2.0](LICENSE)

