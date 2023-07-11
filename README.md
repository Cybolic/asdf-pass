<div align="center">

# asdf-pass [![Build](https://github.com/Cybolic/asdf-pass/actions/workflows/build.yml/badge.svg)](https://github.com/Cybolic/asdf-pass/actions/workflows/build.yml) [![Lint](https://github.com/Cybolic/asdf-pass/actions/workflows/lint.yml/badge.svg)](https://github.com/Cybolic/asdf-pass/actions/workflows/lint.yml)

[pass](https://www.passwordstore.org/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add pass
# or
asdf plugin add pass https://github.com/Cybolic/asdf-pass.git
```

pass:

```shell
# Show all installable versions
asdf list-all pass

# Install specific version
asdf install pass latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pass latest

# Now pass commands are available
pass --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Cybolic/asdf-pass/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Christian Dannie Storgaard](https://github.com/Cybolic/)
