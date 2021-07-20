<div align="center">

# asdf-tomcat [![Build](https://github.com/yoerayo/asdf-tomcat/actions/workflows/build.yml/badge.svg)](https://github.com/yoerayo/asdf-tomcat/actions/workflows/build.yml) [![Lint](https://github.com/yoerayo/asdf-tomcat/actions/workflows/lint.yml/badge.svg)](https://github.com/yoerayo/asdf-tomcat/actions/workflows/lint.yml)


[tomcat](https://github.com/apache/tomcat) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add tomcat
# or
asdf plugin add tomcat https://github.com/yoerayo/asdf-tomcat.git
```

tomcat:

```shell
# Show all installable versions
asdf list-all tomcat

# Install specific version
asdf install tomcat latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tomcat latest

# Now tomcat commands are available
tomcat --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/yoerayo/asdf-tomcat/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Keith Starling](https://github.com/yoerayo/)
