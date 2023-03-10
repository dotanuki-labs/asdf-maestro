<div align="center">

# asdf-maestro [![Build](https://github.com/dotanuki-labs/asdf-maestro/actions/workflows/build.yml/badge.svg)](https://github.com/dotanuki-labs/asdf-maestro/actions/workflows/build.yml) [![Lint](https://github.com/dotanuki-labs/asdf-maestro/actions/workflows/lint.yml/badge.svg)](https://github.com/dotanuki-labs/asdf-maestro/actions/workflows/lint.yml)


[maestro](https://github.com/mobile-dev-inc/maestro) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add maestro
# or
asdf plugin add maestro https://github.com/dotanuki-labs/asdf-maestro.git
```

maestro:

```shell
# Show all installable versions
asdf list-all maestro

# Install specific version
asdf install maestro latest

# Set a version globally (on your ~/.tool-versions file)
asdf global maestro latest

# Now maestro commands are available
maestro --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dotanuki-labs/asdf-maestro/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ubiratan Soares](https://github.com/dotanuki-labs/)
