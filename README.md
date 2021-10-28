<div align="center">

# asdf-hranoprovod [![Build](https://github.com/aquilax/asdf-hranoprovod/actions/workflows/build.yml/badge.svg)](https://github.com/aquilax/asdf-hranoprovod/actions/workflows/build.yml) [![Lint](https://github.com/aquilax/asdf-hranoprovod/actions/workflows/lint.yml/badge.svg)](https://github.com/aquilax/asdf-hranoprovod/actions/workflows/lint.yml)


[hranoprovod](https://hranoprovod.readthedocs.io/en/latest/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add hranoprovod
# or
asdf plugin add hranoprovod https://github.com/aquilax/asdf-hranoprovod.git
```

hranoprovod:

```shell
# Show all installable versions
asdf list-all hranoprovod

# Install specific version
asdf install hranoprovod latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hranoprovod latest

# Now hranoprovod commands are available
hranoprovod-cli --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/aquilax/asdf-hranoprovod/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Evgeniy Vasilev](https://github.com/aquilax/)
