# 123Math

A simple Python library for basic math operations: addition and subtraction.

## Folder Structure

- `src/` - Source code for math operations
- `tests/` - Pytest test cases
- `default/requirements.txt` - Project dependencies
- `default/README.md` - This file
- `default/math.json` - CI workflow metadata

## Usage

```
from src.math_operations import add, subtract

print(add(2, 3))        # Output: 5
print(subtract(5, 3))   # Output: 2
```

## Running Tests

Install dependencies:

```
pip install -r default/requirements.txt
```

Run all tests:

```
python -m pytest tests/ -v --tb=short
```

## CI/CD

See `.github/workflows/ci.yml` for the GitHub Actions workflow.
