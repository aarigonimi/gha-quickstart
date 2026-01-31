# GitHub Actions Learning (Python)

A minimal repo to learn GitHub Actions with Python. Each workflow builds on the previous one.

## Quick Start

1. Fork or clone this repo
2. Push to your GitHub account
3. Open the **Actions** tab to see workflows run

## Workflows

| Workflow | What you'll learn |
|----------|-------------------|
| [01-hello-world](.github/workflows/01-hello-world.yml) | Checkout, setup Python, run a script |
| [02-matrix-test](.github/workflows/02-matrix-test.yml) | Matrix strategy (multiple Python versions) |
| [03-lint-and-test](.github/workflows/03-lint-and-test.yml) | Multiple jobs, dependencies, lint + test |

## Run Locally

```bash
cd python
pip install -r requirements.txt
python hello.py
pytest test_calculator.py -v
```
