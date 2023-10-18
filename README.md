pre-commit liquidsoap
=====================

Pre-commit hooks for liquidsoap scripts. Currently supports script formatting.

To use, add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/savonet/pre-commit-liquidsoap
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: liquidsoap-prettier
```
