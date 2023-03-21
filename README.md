# asdf-maestro

[![CI](https://github.com/dotanuki-labs/asdf-maestro/actions/workflows/ci.yml/badge.svg)](https://github.com/dotanuki-labs/asdf-maestro/actions/workflows/ci.yml)
[![Code Style](https://img.shields.io/badge/code%20style-%E2%9D%A4-FF4081.svg)](https://shellcheck.net/)
[![License](https://img.shields.io/github/license/dotanuki-labs/asdf-maestro)](https://choosealicense.com/licenses/mit)


A [maestro](https://github.com/mobile-dev-inc/maestro) plugin for [asdf](https://github.com/asdf-vm/asdf).


## Installing

Installing this plugin:

```bash
$> asdf plugin add maestro https://github.com/dotanuki-labs/asdf-maestro.git
```

## Using

Managing `maestro` with `asdf`:

```bash

# Show all installable versions
$> asdf list-all maestro

# Download the latest version
$> asdf install maestro latest

# Define the latest version for your local project (writes <project>/.tool-versions)
$> asdf local maestro latest

# Now maestro commands are available
$> maestro --version

# Rollback/install a previous version
$> asdf install maestro 1.24.0
$> asdf local maestro 1.24.0

```

You may also want to check the [official documentation](https://asdf-vm.com/) to learn more about `asdf`.

## License

Copyright (c) 2023 - Dotanuki Labs - [The MIT license](https://choosealicense.com/licenses/mit/)

