<div align="center">

# asdf-brew-php [![Build](https://github.com/yogurt1/asdf-brew-php/actions/workflows/build.yml/badge.svg)](https://github.com/yogurt1/asdf-brew-php/actions/workflows/build.yml) [![Lint](https://github.com/yogurt1/asdf-brew-php/actions/workflows/lint.yml/badge.svg)](https://github.com/yogurt1/asdf-brew-php/actions/workflows/lint.yml)


[php](asdf-brew-php) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `brew` homebrew app
- `jq` for queries PHP versions from homebrew

# Install

Plugin:

```shell
asdf plugin add php
# or
asdf plugin add php https://github.com/yogurt1/asdf-brew-php.git
```

brew-php:

```shell
# Show all installable versions
asdf list-all php

# Install specific version
asdf install php latest

# Set a version globally (on your ~/.tool-versions file)
asdf global php latest

# Now php commands are available
php --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/yogurt1/asdf-brew-php/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Paruyr](https://github.com/yogurt1/)
