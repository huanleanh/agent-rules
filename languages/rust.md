# Rust Guidelines

- **Ownership**: Understand and respect ownership/borrowing rules. Prefer references over cloning.
- **Pattern Matching**: Exhaustive `match` statements for Enums/Options.
- **Error Handling**: Use `Result<T, E>` and `Option<T>`. Use `?` operator for propagation.
- **Cargo**: Use `cargo fmt` and `cargo clippy` regularly.
- **Safety**: Avoid `unsafe` unless strictly necessary for performance or FFI.
- **Naming**: `snake_case` for variables/functions, `PascalCase` for types/enums.
- **Async**: Use `tokio` for async runtimes.
