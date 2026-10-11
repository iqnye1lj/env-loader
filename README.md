# env-loader

A tiny dotenv parser that coerces values into ints, floats and booleans.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install env-loader
```

## Usage

```python
from env_loader import envLoader

result = envLoader("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
