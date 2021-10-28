# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test hranoprovod https://github.com/aquilax/asdf-hranoprovod.git "hranoprovod-cli --help"
```

Tests are automatically run in GitHub Actions on push and PR.
