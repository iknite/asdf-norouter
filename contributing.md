# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test norouter https://github.com/iknite/asdf-norouter.git "norouter show-installer"
```

Tests are automatically run in GitHub Actions on push and PR.
