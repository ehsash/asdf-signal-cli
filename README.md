<div align="center">

# asdf-signal-cli [![Build](https://github.com/ehsash/asdf-signal-cli/actions/workflows/build.yml/badge.svg)](https://github.com/ehsash/asdf-signal-cli/actions/workflows/build.yml) [![Lint](https://github.com/ehsash/asdf-signal-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/ehsash/asdf-signal-cli/actions/workflows/lint.yml)

[signal-cli](https://github.com/AsamK/signal-cli/wiki/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add signal-cli
# or
asdf plugin add signal-cli https://github.com/ehsash/asdf-signal-cli.git
```

signal-cli:

```shell
# Show all installable versions
asdf list-all signal-cli

# Install specific version
asdf install signal-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global signal-cli latest

# Now signal-cli commands are available
signal-cli --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ehsash/asdf-signal-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ehsash Tehel](https://github.com/ehsash/)
