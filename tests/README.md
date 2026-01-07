# Tests

This directory contains all test files for the Giza Voxel Simulation project.

## Test Structure

- `unit/` - Unit tests for individual components
- `integration/` - Integration tests for component interactions
- `performance/` - Performance and benchmarking tests

## Running Tests

```bash
# Run all tests
python -m pytest tests/

# Run specific test file
python -m pytest tests/unit/test_example.py

# Run with coverage
python -m pytest --cov=src tests/
```

## Test Requirements

Install testing dependencies:
```bash
pip install pytest pytest-cov
```
