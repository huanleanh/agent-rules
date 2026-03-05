# C# Guidelines

- **Version**: Target .NET 6/7/8.
- **Naming**: `PascalCase` for classes and methods. `camelCase` for private fields (prefix with `_`).
- **Async**: Use `Task`, `async`, and `await`. Avoid `Task.Result`.
- **DI**: Use built-in Dependency Injection in .NET Core.
- **LINQ**: Use LINQ for collection queries but avoid over-complexity.
- **Properties**: Use auto-implemented properties.
- **Testing**: xUnit or NUnit with FluentAssertions.
