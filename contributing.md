# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test ruff-tools https://github.com/purajit/asdf-ruff-tools.git "ruff-tools --version"
```

Tests are automatically run in GitHub Actions on push and PR.
