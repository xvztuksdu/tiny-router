# tiny-router

A very small path router with named parameters and method matching.

## Why

Mostly written for my own projects, but it may be useful to someone else.

## Install

```bash
pip install tiny-router
```

## Usage

```python
from tiny_router import tinyRouter

result = tinyRouter("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
