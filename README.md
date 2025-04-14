# extended-functools

Remember to:

1. Replace all instances of `extended-functools` with the real name of the project
2. Replace all instances of `extended_functools` with the "package name" of the project
3. Rename the source code folder from `extended_functools` to your package name
4. Generate a lock file (`uv sync`)
5. Rewrite the `README.md`
6. If the project is not an executable, delete the files:
   * `src/extended_functools/main.py`
   * `src/extended_functools/logger.py`
   * `src/extended_functools/logger_config.toml`
   * `src/extended_functools/config.py`
   * `python-dotenv` and `tomli` as dependencies in `pyproject.toml` (unless otherwise needed)
