# Ruby Guidelines

- **Code Style**: Follow the Ruby Style Guide (RuboCop default).
- **Rails**: Thin controllers, fat models (or move logic to Service Objects).
- **Naming**: `snake_case` for variables/methods, `PascalCase` for classes/modules.
- **Iterators**: Use `each`, `map`, `select` over `for` loops.
- **Gems**: Avoid over-reliance on gems. Keep `Gemfile` organized.
- **Testing**: RSpec with Capybara/FactoryBot.
- **Security**: Use strong parameters in Rails. Avoid direct SQL interpolation.
