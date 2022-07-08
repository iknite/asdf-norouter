<div align="center">

# asdf-norouter [![Build](https://github.com/iknite/asdf-norouter/actions/workflows/build.yml/badge.svg)](https://github.com/iknite/asdf-norouter/actions/workflows/build.yml) [![Lint](https://github.com/iknite/asdf-norouter/actions/workflows/lint.yml/badge.svg)](https://github.com/iknite/asdf-norouter/actions/workflows/lint.yml)


[norouter](https://norouter.io/docs/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `norouter.yaml`: configuration yml to be used in a norouter session
- `bash`, `curl`, `ssh`, `kubectl`,`docker`: The local tools you want to use for norouter tunneling.
# Install

Plugin:

```shell
asdf plugin add norouter
# or
asdf plugin add norouter https://github.com/iknite/asdf-norouter.git
```

norouter:

```shell
# Show all installable versions
asdf list-all norouter

# Install specific version
asdf install norouter latest

# Set a version globally (on your ~/.tool-versions file)
asdf global norouter latest

# Now norouter commands are available
norouter show-installer
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/iknite/asdf-norouter/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Enrique Paredes](https://github.com/iknite/)
