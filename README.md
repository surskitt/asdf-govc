<div align="center">

# asdf-govc [![Build](https://github.com/surskitt/asdf-govc/actions/workflows/build.yml/badge.svg)](https://github.com/surskitt/asdf-govc/actions/workflows/build.yml) [![Lint](https://github.com/surskitt/asdf-govc/actions/workflows/lint.yml/badge.svg)](https://github.com/surskitt/asdf-govc/actions/workflows/lint.yml)

[govc](https://developer.broadcom.com/xapis/vsphere-web-services-api/latest/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add govc
# or
asdf plugin add govc https://github.com/surskitt/asdf-govc.git
```

govc:

```shell
# Show all installable versions
asdf list-all govc

# Install specific version
asdf install govc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global govc latest

# Now govc commands are available
govc version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/surskitt/asdf-govc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [surskitt](https://github.com/surskitt/)
