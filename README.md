<div align="center">

# asdf-coredns [![Build](https://github.com/s3than/asdf-coredns/actions/workflows/build.yml/badge.svg)](https://github.com/s3than/asdf-coredns/actions/workflows/build.yml) [![Lint](https://github.com/s3than/asdf-coredns/actions/workflows/lint.yml/badge.svg)](https://github.com/s3than/asdf-coredns/actions/workflows/lint.yml)


[coredns](https://coredns.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add coredns
# or
asdf plugin add coredns https://github.com/s3than/asdf-coredns.git
```

coredns:

```shell
# Show all installable versions
asdf list-all coredns

# Install specific version
asdf install coredns latest

# Set a version globally (on your ~/.tool-versions file)
asdf global coredns latest

# Now coredns commands are available
coredns --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/s3than/asdf-coredns/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tim Colbert](https://github.com/s3than/)
