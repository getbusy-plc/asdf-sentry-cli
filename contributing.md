# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test sentry-cli https://github.com/MacPaw/asdf-sentry-cli.git "sentry-cli --help"
```

Tests are automatically run in GitHub Actions on push and PR.
