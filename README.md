<div align="center">

# asdf-jj-vcs [![Build](https://github.com/myhops/asdf-jj-vcs/actions/workflows/build.yml/badge.svg)](https://github.com/myhops/asdf-jj-vcs/actions/workflows/build.yml) [![Lint](https://github.com/myhops/asdf-jj-vcs/actions/workflows/lint.yml/badge.svg)](https://github.com/myhops/asdf-jj-vcs/actions/workflows/lint.yml)

[jj-vcs](https://jj-vcs.github.io/jj/latest/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add jj-vcs
# or
asdf plugin add jj-vcs https://github.com/myhops/asdf-jj-vcs.git
```

jj-vcs:

```shell
# Show all installable versions
asdf list-all jj-vcs

# Install specific version
asdf install jj-vcs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jj-vcs latest

# Now jj-vcs commands are available
jj version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/myhops/asdf-jj-vcs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Zandbergen](https://github.com/myhops/)
