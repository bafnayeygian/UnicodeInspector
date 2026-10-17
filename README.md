# UnicodeInspector

Inspect text for zero-width characters, bidirectional controls, unusual Unicode, and invisible formatting marks.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/UnicodeInspector.git
cd UnicodeInspector
python -m pip install .
```

## Quick start

```bash
unicode-inspector --help
```

Useful for source-code review, copied text, Persian/Arabic text debugging, and detecting invisible formatting controls.

```bash
unicode-inspector suspicious.txt
```

## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
