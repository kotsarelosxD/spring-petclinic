"""
# Build and Run Instructions

This is a Java Spring Boot project.

## Prerequisites

- Java 13 or higher
- Gradle

## Build

To build the project, run the following command:

```bash
./gradlew build
```

This will compile the code, run the tests, and package the application into a JAR file in the `build/libs` directory.

## Run

You can run the application in several ways:

### 1. Using Java
After building the project, you can run the application from the command line using:

```bash
java -jar build/libs/spring-petclinic-*.jar
```

### 2. Using Gradle
You can also run the application directly using the Spring Boot Gradle plugin:

```bash
./gradlew bootRun
```

### 3. Native Image
To build and run a native image of the application, use the following commands:

```bash
./gradlew nativeCompile
./build/libs/spring-petclinic
```

### 4. Docker Compose
You can also run the application using Docker Compose:

```bash
docker-compose up
```
"""