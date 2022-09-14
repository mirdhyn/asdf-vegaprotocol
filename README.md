<div align="center">

# asdf-vegaprotocol [![Build](https://github.com/mirdhyn/asdf-vegaprotocol/actions/workflows/build.yml/badge.svg)](https://github.com/mirdhyn/asdf-vegaprotocol/actions/workflows/build.yml) [![Lint](https://github.com/mirdhyn/asdf-vegaprotocol/actions/workflows/lint.yml/badge.svg)](https://github.com/mirdhyn/asdf-vegaprotocol/actions/workflows/lint.yml)


[vegaprotocol](https://github.com/vegaprotocol/vega) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add vegaprotocol
# or
asdf plugin add vegaprotocol https://github.com/mirdhyn/asdf-vegaprotocol.git
```

vegaprotocol:

```shell
# Show all installable versions
asdf list-all vegaprotocol

# Install specific version
asdf install vegaprotocol latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vegaprotocol latest

# Now vegaprotocol commands are available
vega --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mirdhyn/asdf-vegaprotocol/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Merlin Gaillard](https://github.com/mirdhyn/)
