# Build and Run Instructions

This is a Java Spring Boot project.

## Prerequisites

- Java 17 or higher
- Maven

## Build

To build the project, run the following command:

```bash
./mvnw install
```

This will compile the code, run the tests, and package the application into a JAR file in the `target` directory.

## Run

You can run the application in several ways:

### 1. Using Java
After building the project, you can run the application from the command line using:

```bash
java -jar target/spring-petclinic-*.jar
```

### 2. Using Maven
You can also run the application directly using the Spring Boot Maven plugin:

```bash
./mvnw spring-boot:run
```

### 3. Native Image
To build and run a native image of the application, use the following commands:

```bash
./mvnw native:compile
./target/spring-petclinic
```

### 4. Docker Compose
You can also run the application using Docker Compose:

```bash
docker-compose up
```

Signed-off-by: kotsarelos <64009385+kotsarelosxD@users.noreply.github.com>