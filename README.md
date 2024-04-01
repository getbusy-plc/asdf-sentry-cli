<div align="center">

# asdf-sentry-cli [![Build](https://github.com/MacPaw/asdf-sentry-cli/actions/workflows/build.yml/badge.svg)](https://github.com/MacPaw/asdf-sentry-cli/actions/workflows/build.yml) [![Lint](https://github.com/MacPaw/asdf-sentry-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/MacPaw/asdf-sentry-cli/actions/workflows/lint.yml)

[sentry-cli](https://github.com/getsentry/sentry-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add sentry-cli
# or
asdf plugin add sentry-cli https://github.com/MacPaw/asdf-sentry-cli.git
```

sentry-cli:

```shell
# Show all installable versions
asdf list-all sentry-cli

# Install specific version
asdf install sentry-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sentry-cli latest

# Now sentry-cli commands are available
sentry-cli --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MacPaw/asdf-sentry-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [MacPaw](https://github.com/MacPaw/)
