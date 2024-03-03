![header](asset/header.png)
# MDST-Tutorials

Additional tutorial materials for MDST member.

They are **NOT** required for the onboarding/admission process but useful to know and could help in certain project groups.

# Development Setup

Run the following commands:

```
pip install pre-commit
pre-commit install
```

## Ruff

[Ruff](https://docs.astral.sh/ruff/) will automatically check all code diffs for style violations but will not attempt a fix. It will generate false positives so only fix errors that make sense to you.

Auto fix one particular error code:

`ruff check select=<error code> --fix`

When done, commit with the `--no-verify` option to skip the pre-commit checks.