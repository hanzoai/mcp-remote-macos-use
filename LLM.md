# LLM.md - Hanzo Mcp Remote Macos Use

## Overview
MCP server that enables AI to fully control remote macOS systems

## Tech Stack
- **Language**: Python

## Build & Run
```bash
uv sync
uv run pytest
```

## Structure
```
mcp-remote-macos-use/
  Dockerfile
  LICENSE
  README.md
  compose.yml
  conftest.py
  pyproject.toml
  pytest.ini
  src/
  test_mcp_local.py
  tests/
  uv.lock
```

## Key Files
- `README.md` -- Project documentation
- `pyproject.toml` -- Python project config
- `Dockerfile` -- Container build
- `compose.yml` -- Docker Compose services
