# Java Guidelines

- **JVM Version**: Target Java 17+ (LTS).
- **Naming**: `camelCase` for variables/methods, `PascalCase` for classes/interfaces.
- **Streams**: Use Java Streams for collection manipulation where readable.
- **Concurrency**: Prefer `java.util.concurrent` (Executors, CompletableFuture) over raw Threads.
- **Spring Boot**: Follow standard architectural layers (Controller, Service, Repository, DTO).
- **Dependency**: Use Maven or Gradle. Keep dependencies updated.
- **Testing**: JUnit 5 and Mockito. Goal: high branch coverage.
- **Immutability**: Use `record` for data classes.
