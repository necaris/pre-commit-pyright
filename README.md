# pre-commit for pyright
Wrapper to enable pre-commit hook usage for pyright

## Usage:
In your `.pre-commit-config.yaml` include the following block.

```
-   repo: https://github.com/necaris/pre-commit-pyright
    rev: '2019.05.31'
    hooks:
    -   id: pytype
```

