# slugify

Transliterates and normalises text into slugs suitable for URLs and filenames.

## Why

I wanted something I could read in one sitting and vendor into a project if needed.

## Install

```bash
pip install slugify
```

## Usage

```python
from slugify import slugify

result = slugify("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
