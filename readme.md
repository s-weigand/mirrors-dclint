# Archived

Use the official hook from https://github.com/docker-compose-linter/pre-commit-dclint instead


## dclint mirror

Mirror of dclint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For dclint: see https://github.com/zavoloklom/docker-compose-linter

## Using dclint with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/s-weigand/mirrors-dclint
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: dclint
```
