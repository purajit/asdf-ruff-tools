<div align="center">

# asdf-ruff-tools [![Build](https://github.com/purajit/asdf-ruff-tools/actions/workflows/build.yml/badge.svg)](https://github.com/purajit/asdf-ruff-tools/actions/workflows/build.yml) [![Lint](https://github.com/purajit/asdf-ruff-tools/actions/workflows/lint.yml/badge.svg)](https://github.com/purajit/asdf-ruff-tools/actions/workflows/lint.yml)

[ruff-tools](https://github.com/purajit/ruff-tools) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add ruff-tools
# or
asdf plugin add ruff-tools https://github.com/purajit/asdf-ruff-tools.git
```

ruff-tools:

```shell
# Show all installable versions
asdf list-all ruff-tools

# Install specific version
asdf install ruff-tools latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ruff-tools latest

# Now ruff-tools commands are available
ruff-tools --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/purajit/asdf-ruff-tools/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [purajit](https://github.com/purajit/)
