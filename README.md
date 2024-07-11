<div align="center">

# asdf-rke2 [![Build](https://github.com/lindhe/asdf-rke2/actions/workflows/build.yml/badge.svg)](https://github.com/lindhe/asdf-rke2/actions/workflows/build.yml) [![Lint](https://github.com/lindhe/asdf-rke2/actions/workflows/lint.yml/badge.svg)](https://github.com/lindhe/asdf-rke2/actions/workflows/lint.yml)

[rke2](https://docs.rke2.io) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `sh`, `curl`
- `INSTALL_RKE2_VERSION`: optionally set this environment variable to target a specific version of RKE2.

# Install

Plugin:

```shell
asdf plugin add rke2
# or
asdf plugin add rke2 https://github.com/lindhe/asdf-rke2.git
```

rke2:

```shell
# Show all installable versions
asdf list-all rke2

# Install specific version
asdf install rke2 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rke2 latest

# Now rke2 commands are available
rke2 --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lindhe/asdf-rke2/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andreas Lindhé](https://github.com/lindhe/)
