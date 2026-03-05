# Go Guidelines

- **Simplicity**: Favor explicit over implicit. Keep functions short.
- **Error Handling**: Always check errors. Don't use `panic` for expected errors.
- **Concurrency**: Use Goroutines and Channels. Prefer `sync.WaitGroup` or `context` for coordination.
- **Naming**: `camelCase` or `PascalCase` (for export). Keep names concise.
- **Formating**: Use `gofmt` and `goimports`.
- **Interfaces**: Accept interfaces, return structs. Keep interfaces small.
- **Modules**: Always use Go modules (`go.mod`).
