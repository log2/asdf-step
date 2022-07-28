<div align="center">

# asdf-step [![Build](https://github.com/log2/asdf-step/actions/workflows/build.yml/badge.svg)](https://github.com/log2/asdf-step/actions/workflows/build.yml) [![Lint](https://github.com/log2/asdf-step/actions/workflows/lint.yml/badge.svg)](https://github.com/log2/asdf-step/actions/workflows/lint.yml)


[step](https://github.com/smallstep/cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add step
# or
asdf plugin add step https://github.com/log2/asdf-step.git
```

step:

```shell
# Show all installable versions
asdf list-all step

# Install specific version
asdf install step latest

# Set a version globally (on your ~/.tool-versions file)
asdf global step latest

# Now step commands are available
step --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/log2/asdf-step/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Lorenzo Gallucci](https://github.com/log2/)
