# C++ Guidelines

- **Modern C++**: Target C++17 or C++20. Use `auto` where appropriate.
- **Memory**: Use smart pointers (`std::unique_ptr`, `std::shared_ptr`). Avoid manual `new`/`delete`.
- **STL**: Utilize the Standard Template Library.
- **RAII**: Resource Acquisition Is Initialization.
- **Naming**: `snake_case` or `lowerCamelCase` for variables. `PascalCase` for classes. `UPPER_SNAKE` for macros.
- **Performance**: Pass by `const &` to avoid copies.
- **Headers**: Use `#pragma once` for header guards.
