# Heektime Schema for Python

## Prerequisites

- Python
- [Poetry]

## Generate

```bash
python -m grpc_tools.protoc \
  -I/path/to/heektime-schema \
  --python_out=. \
  --grpc_python_out=. \
  /path/to/heektime-schema/heektime-schema/**/*.proto
```

## Build

```bash
poetry build
```

[Poetry]: https://python-poetry.org/
