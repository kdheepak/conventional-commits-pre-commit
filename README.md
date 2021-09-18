# Conventional commits pre-commit hook

```yaml
# Make sure to set the default_stages in your config file
# to prevent installing hooks multiple times inadvertently
default_stages: [commit]

repos:
  - repo: https://github.com/kdheepak/conventional-commits-pre-commit
    rev: v0.2.0
    hooks:
      - id: check-commit-msg
```

Then run `pre-commit install -t commit-msg` and you're ready to go.
