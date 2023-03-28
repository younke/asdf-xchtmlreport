<div align="center">

# asdf-xchtmlreport [![Build](https://github.com/younke/asdf-xchtmlreport/actions/workflows/build.yml/badge.svg)](https://github.com/younke/asdf-xchtmlreport/actions/workflows/build.yml) [![Lint](https://github.com/younke/asdf-xchtmlreport/actions/workflows/lint.yml/badge.svg)](https://github.com/younke/asdf-xchtmlreport/actions/workflows/lint.yml)


[XCTestHTMLReport](https://github.com/XCTestHTMLReport/XCTestHTMLReport) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Supported Versions

Versions above 2.3.0. Installer will use binary executable provided with release.
**Installation might be broken** if tool maintainer somehow change release assets.

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`

# Install

Plugin:

```shell
asdf plugin add xchtmlreport
# or
asdf plugin add xchtmlreport https://github.com/younke/asdf-xchtmlreport.git
```

xchtmlreport:

```shell
# Show all installable versions
asdf list-all xchtmlreport

# Install specific version
asdf install xchtmlreport latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xchtmlreport latest

# Now xchtmlreport commands are available
xchtmlreport -h
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/younke/asdf-xchtmlreport/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Vasily Ptitsyn](https://github.com/younke/)
