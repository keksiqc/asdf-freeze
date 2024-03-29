<div align="center">

# asdf-freeze [![Build](https://github.com/keksiqc/asdf-freeze/actions/workflows/build.yml/badge.svg)](https://github.com/keksiqc/asdf-freeze/actions/workflows/build.yml) [![Lint](https://github.com/keksiqc/asdf-freeze/actions/workflows/lint.yml/badge.svg)](https://github.com/keksiqc/asdf-freeze/actions/workflows/lint.yml)

[freeze](https://github.com/charmbracelet/freeze) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add freeze https://github.com/keksiqc/asdf-freeze.git
```

freeze:

```shell
# Show all installable versions
asdf list-all freeze

# Install specific version
asdf install freeze latest

# Set a version globally (on your ~/.tool-versions file)
asdf global freeze latest

# Now freeze commands are available
freeze --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/keksiqc/asdf-freeze/graphs/contributors)!

# Thanks

This repository is adapted from [asdf-gum](https://github.com/lwiechec/asdf-gum) by
[Lukasz Wiechec](https://github.com/lwiechec).

# License

Distributed under the [Eclipse Public License](LICENSE), the same as `asdf-babashka`.
© [Lukasz Wiechec](https://github.com/lwiechec)
