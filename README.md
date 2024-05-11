<div align="center">

# asdf-llamafile [![Build](https://github.com/number5/asdf-llamafile/actions/workflows/build.yml/badge.svg)](https://github.com/number5/asdf-llamafile/actions/workflows/build.yml) [![Lint](https://github.com/number5/asdf-llamafile/actions/workflows/lint.yml/badge.svg)](https://github.com/number5/asdf-llamafile/actions/workflows/lint.yml)

[llamafile](https://llamafile.ai/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add llamafile
# or
asdf plugin add llamafile https://github.com/number5/asdf-llamafile.git
```

llamafile:

```shell
# Show all installable versions
asdf list-all llamafile

# Install specific version
asdf install llamafile latest

# Set a version globally (on your ~/.tool-versions file)
asdf global llamafile latest

# Now llamafile commands are available
llamafile --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/number5/asdf-llamafile/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bruce Wang](https://github.com/number5/)
