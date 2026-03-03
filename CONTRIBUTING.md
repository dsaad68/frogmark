# Contributing to Frogmouth

Thank you for your interest in contributing to Frogmouth!

## Branching Strategy

This project uses the following branching model:

- **`main`** – stable, production-ready code.
- **`dev`** – active development branch. All new features and fixes should be branched from `dev` and merged back into `dev` via pull requests.

## Getting Started

1. Fork the repository.
2. Clone your fork locally.
3. Create a feature branch from `dev`:

   ```
   git checkout dev
   git checkout -b feature/your-feature-name
   ```

4. Make your changes and commit them with a clear message.
5. Push your branch and open a pull request targeting the `dev` branch.

## Code Style

This project uses [pylint](https://pylint.org/) for linting. Run the linter before submitting:

```
make lint
```

## Running the App Locally

Install dependencies with [Poetry](https://python-poetry.org/):

```
poetry install
poetry run frogmouth
```
