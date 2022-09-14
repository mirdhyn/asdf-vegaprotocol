# asdf-vegaprotocol

[vegaprotocol](https://github.com/vegaprotocol/vega) plugin for the [asdf version manager](https://asdf-vm.com).

## Install

```
asdf plugin add vega https://github.com/mirdhyn/asdf-vegaprotocol.git
```

## Usage

```
# Show all installable versions
asdf list-all vega

# Install specific version
asdf install vega latest

# List installed versions
asdf list vega

# Set a version globally (on your ~/.tool-versions file)
asdf global vega latest

# Now vegaprotocol commands are available
vega --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.
