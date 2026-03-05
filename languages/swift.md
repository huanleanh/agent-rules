# Swift Guidelines

- **Style**: Follow Apple Swift API Design Guidelines.
- **Concurrency**: Use `async/await` and `actor`. Avoid `DispatchQueue.main.async` if possible in favor of `@MainActor`.
- **Safety**: Avoid force unwrapping (`!`). Use `if let` or `guard let`.
- **Memory**: Use `weak self` in closures to avoid retain cycles.
- **UI**: Prefer SwiftUI for new features. Use `Codeable` for JSON.
- **Naming**: `camelCase` for everything except type names (`PascalCase`).
- **Tests**: XCTest or Swift Testing (Xcode 16+).
