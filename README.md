<div align="center">

# asdf-buck2 [![Build](https://github.com/izaakschroeder/asdf-buck2/actions/workflows/build.yml/badge.svg)](https://github.com/izaakschroeder/asdf-buck2/actions/workflows/build.yml) [![Lint](https://github.com/izaakschroeder/asdf-buck2/actions/workflows/lint.yml/badge.svg)](https://github.com/izaakschroeder/asdf-buck2/actions/workflows/lint.yml)

[buck2](https://buck2.build/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add buck2
# or
asdf plugin add buck2 https://github.com/izaakschroeder/asdf-buck2.git
```

buck2:

```shell
# Show all installable versions
asdf list-all buck2

# Install specific version
asdf install buck2 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global buck2 latest

# Now buck2 commands are available
buck2 --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/izaakschroeder/asdf-buck2/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Izaak Schroeder](https://github.com/izaakschroeder/)
