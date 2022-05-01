# Gradle multi-module project

This is a sample gradle multi-module spring-boot project.
It consists of two modules:

    └── library
    └── application

The `library` module is not a stand-alone Spring Boot application. It is used by the `application` module as a dependency instead.


## Build and run the application

You can start the application in your IDE or use the command line. Once the application is running, visit the client application in the browser, at `http://localhost:8080/`. There, you should see `Hello, World` reflected in the response.

```
$ ./gradlew build && ./gradlew :application:bootRun
```
