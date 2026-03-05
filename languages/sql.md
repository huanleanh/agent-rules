# SQL Guidelines

- **Keywords**: Use UPPERCASE for SQL keywords (`SELECT`, `FROM`, `WHERE`).
- **Formatting**: Use indentation for clarity. Place each column on a new line in complex queries.
- **Security**: Avoid raw queries; use ORMs or prepared statements.
- **Optimization**: Use `EXPLAIN` to analyze query performance. Ensure proper indexing.
- **Joins**: Prefer explicit `JOIN` syntax over comma-separated lists.
- **Aliases**: Use descriptive aliases for tables and calculated columns.
