# Python CI/CD Demo

A small Python calculator project for practicing:

- Git
- GitHub Actions
- CI/CD
- pytest
- test coverage
- SonarCloud

## Run locally

Create and activate a virtual environment, then install:

```bash
pip install -r requirements-dev.txt
```

Run tests:

```bash
pytest
```

Run tests with coverage:

```bash
pytest --cov=app --cov-report=term-missing
```
