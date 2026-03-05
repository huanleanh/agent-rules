# Shell/Bash Guidelines

- **Shebang**: Use `#!/usr/bin/env bash`.
- **Safety**: Use `set -euo pipefail`.
- **Quoting**: Always quote variables (`"$VAR"`) to prevent word splitting.
- **Logic**: Use `[[ ... ]]` for tests instead of `[ ... ]`.
- **Style**: Use `camelCase` or `snake_case` for variables. Functions should be `snake_case`.
- **Errors**: Provide helpful error messages and exit codes.
- **Linting**: Use `shellcheck`.
