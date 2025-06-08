## Setup

`uv run tox`

Then edit `pyproject.toml` and uncomment `setenv = { TESTENV = "{env:TESTENV:hello}" }`, and run `uv run tox` again.

This triggers a circular dependency.

How can you use env substitution in `set_env` with shared base environment config?
