# Java Memory Test

## Pre requisites
- JVM, which ever you use for programming
- VisualVM, connects to JVM on runtime, facilitates,
  - Execute GC on specific
  - See Memory, CPU, Threads, Net consuming
  - Obtain a Heap dump on a specific time
- JMetter, simulates load, used in this example for test HTTP GET method
- MAT, Eclipse Memory Analyzer. Used to analize Heap dump files, facilitates identification of possible memory leaks identifying classes which consume more memory
- Java project: In this example a SpringBoot app was created exposing "/" path which resolves a string

## Example App testing

```
% curl http://localhost:8080/
Greetings from Spring Boot!
```

## Memory analysis PoC
