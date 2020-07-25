# Heektime Schema for Python

## Prerequisites

- Python
- [Poetry]

## Generate

```bash
python -m grpc_tools.protoc \
  -I/path/to/heektime-schema \
  --python_out=./heektime_schema
  --grpc_python_out=./heektime_schema \
  /path/to/heektime-schema/*.proto
```

## Build

```bash
poetry build
```

[Poetry]: https://python-poetry.org/
