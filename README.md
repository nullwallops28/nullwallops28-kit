# nullwallops28-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m nullwallops28_kit.cli --help
```

```python
from nullwallops28_kit.core import Nullwallops28Tool

tool = Nullwallops28Tool()
print(tool)
```

## Layout

```
nullwallops28_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 nullwallops28
