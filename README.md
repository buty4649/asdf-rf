<div align="center">

# asdf-rf [![Build](https://github.com/buty4649/asdf-rf/actions/workflows/build.yml/badge.svg)](https://github.com/buty4649/asdf-rf/actions/workflows/build.yml) [![Lint](https://github.com/buty4649/asdf-rf/actions/workflows/lint.yml/badge.svg)](https://github.com/buty4649/asdf-rf/actions/workflows/lint.yml)


[rf](https://github.com/buty4649/rf) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add rf
# or
asdf plugin add rf https://github.com/buty4649/asdf-rf.git
```

rf:

```shell
# Show all installable versions
asdf list-all rf

# Install specific version
asdf install rf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rf latest

# Now rf commands are available
rf -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/buty4649/asdf-rf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [buty4649](https://github.com/buty4649/)
