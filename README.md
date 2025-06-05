<div align="center">

# asdf-cloud-provider-kind [![Build](https://github.com/farkasmate/asdf-cloud-provider-kind/actions/workflows/build.yml/badge.svg)](https://github.com/farkasmate/asdf-cloud-provider-kind/actions/workflows/build.yml) [![Lint](https://github.com/farkasmate/asdf-cloud-provider-kind/actions/workflows/lint.yml/badge.svg)](https://github.com/farkasmate/asdf-cloud-provider-kind/actions/workflows/lint.yml)

[cloud-provider-kind](https://github.com/kubernetes-sigs/cloud-provider-kind) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add cloud-provider-kind
# or
asdf plugin add cloud-provider-kind https://github.com/farkasmate/asdf-cloud-provider-kind.git
```

cloud-provider-kind:

```shell
# Show all installable versions
asdf list-all cloud-provider-kind

# Install specific version
asdf install cloud-provider-kind latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cloud-provider-kind latest

# Now cloud-provider-kind commands are available
asdf-cloud-provider-kind --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/farkasmate/asdf-cloud-provider-kind/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mate Farkas](https://github.com/farkasmate/)
