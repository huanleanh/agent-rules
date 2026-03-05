# TypeScript/JavaScript Guidelines

- **Standard**: Follow ESNext and TypeScript latest features.
- **Naming**: `camelCase` for variables/functions, `PascalCase` for classes/types, `UPPER_SNAKE_CASE` for constants.
- **React**: Use functional components with Hooks. Prefer `const [state, setState] = useState(initial)`.
- **Node.js**: Use `async/await`. Avoid callback hell. Use `fs/promises`.
- **Typing**: Avoid `any`. Use `unknown` or specific interfaces. Leverage utility types (`Partial`, `Pick`, etc.).
- **Testing**: Use Jest or Vitest. Mock external services.
- **Tools**: Use ESlint and Prettier.
