## Maven Tutorial Project

This repository contains a simple Java project created to learn and practice the fundamentals of Apache Maven, including project structure, dependency management, build lifecycles, plugins, testing, and packaging.

The project is intended as a hands-on learning environment for understanding how Maven automates Java project builds and dependency resolution. Maven uses a standardized project structure and a pom.xml file to define project configuration, dependencies, and build behavior.

### Repository

[maven-tutorial GitHub Repository](https://github.com/cmoten/maven-tutorial)￼

## Objectives

This project is being used to learn:

* Maven project structure
* The purpose of pom.xml
* Dependency management
* Maven build lifecycles
* Maven plugins
* Unit testing with JUnit
* Packaging Java applications into JAR files
* Running Maven commands from the command line
* IDE integration with Maven

## Project Structure

Typical Maven directory layout:
```text
maven-tutorial/
├── pom.xml
└── src/
    ├── main/
    │   └── java/
    │       └── ...
    └── test/
        └── java/
            └── ...
```

Maven follows a standard directory convention which helps ensure consistency across Java projects.

## Prerequisites

Before running this project, install:

* Java JDK 21 (or compatible version)
* Apache Maven

Verify installations:
```bash
java -version
mvn -version
```

## Common Maven Commands

### Compile the Project
```bash
mvn compile
```
Compiles the Java source code.

### Run Tests

```bash
mvn test
```

Executes unit tests located in:

```text
src/test/java
```

### Package the Application

```bash
mvn package
```

Builds the project and creates a JAR file in the target/ directory.

### Clean Build Artifacts

```bash
mvn clean
```

Removes previously compiled files and build artifacts.

### Full Build

```bash
mvn clean install
```

Performs a full clean build and installs the artifact into the local Maven repository.

## What I Am Learning

This repository is part of a personal learning process focused on:

* Java development workflows
* Build automation
* Dependency management
* Software engineering practices
* Reproducible builds
* Java project organization

## References

* [Apache Maven Official Site](https://maven.apache.org/?utm_source=chatgpt.com)
* [Maven Getting Started Guide](https://maven.apache.org/guides/getting-started/index.html?utm_source=chatgpt.com)
* [GitHub Actions – Java with Maven](https://docs.github.com/en/actions/tutorials/build-and-test-code/java-with-maven?utm_source=chatgpt.com)

## License

This project is for educational and learning purposes.