# Kotlin Guidelines

- **Conventions**: Follow official Kotlin coding conventions.
- **Null Safety**: Use safe calls (`?.`) and Elvis operator (`?:`). Avoid `!!`.
- **Coroutines**: Use Coroutines for async. Handle exceptions with `CoroutineExceptionHandler`.
- **Data Classes**: Use `data class` for models. Use `sealed class` for state machines.
- **Functional**: Use `map`, `filter`, `fold` instead of `for` loops where possible.
- **Android**: Use Jetpack Compose for UI. Follow MVVM/MVI architecture.
- **Testing**: MockK and JUnit.
