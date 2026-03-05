# Python Guidelines

- **PEP 8**: Follow PEP 8 for style. Use `black` for formatting.
- **Typing**: Always include type hints (`def func(a: int) -> str:`).
- **Concurrency**: Use `asyncio` for I/O-bound tasks. Use `multiprocessing` for CPU-bound tasks.
- **Virtual Env**: Use `poetry` or `venv` for dependency management.
- **Testing**: Use `pytest`. Favor fixtures over manual setup.
- **Nomenclature**: `snake_case` for variables/functions, `PascalCase` for classes.
- **Imports**: Absolute imports preferred. Organize imports alphabetically.
