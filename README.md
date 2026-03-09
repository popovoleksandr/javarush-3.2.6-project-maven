# Racer Game Project

A JavaRush project built with Maven and JavaFX game engine.

## Prerequisites

- Java 18+
- Maven 3.6+

## Installation

### 1. Install the Desktop Game Engine JAR

Before building the project, install the desktop game engine dependency into your local Maven repository:

```bash
mvn install:install-file -Dfile=./lib/desktop-game-engine.jar -DgroupId="com.javarush" -DartifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar
```

### 2. Build the Project

```bash
mvn clean install
```

## Running the Application

To run the compiled JAR file:

```bash
java -jar target/project-maven-1.0.jar
```

## Other Useful Commands

**Compile only:**
```bash
mvn compile
```

**Run tests:**
```bash
mvn test
```

**Clean build artifacts:**
```bash
mvn clean
```

**Package without running tests:**
```bash
mvn package -DskipTests
```

## Project Structure

- `src/main/java/` - Main application source code
- `src/test/java/` - Unit tests
- `lib/` - Local JAR dependencies
- `target/` - Build output directory

