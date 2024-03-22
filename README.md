<div align="center">

# asdf-jinjafier [![Build](https://github.com/ORCID/asdf-jinjafier/actions/workflows/build.yml/badge.svg)](https://github.com/ORCID/asdf-jinjafier/actions/workflows/build.yml) [![Lint](https://github.com/ORCID/asdf-jinjafier/actions/workflows/lint.yml/badge.svg)](https://github.com/ORCID/asdf-jinjafier/actions/workflows/lint.yml)


[jinjafier](https://github.com/ORCID/jinjafier) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add jinjafier https://github.com/ORCID/asdf-jinjafier.git
```

jinjafier:

```shell
# Show all installable versions
asdf list-all jinjafier

# Install specific version
asdf install jinjafier latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jinjafier latest

# Now jinjafier commands are available
jinjafier <properties_file>
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

