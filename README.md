<div align="center">

# asdf-xchtmlreport [![Build](https://github.com/younke/asdf-xchtmlreport/actions/workflows/build.yml/badge.svg)](https://github.com/younke/asdf-xchtmlreport/actions/workflows/build.yml) [![Lint](https://github.com/younke/asdf-xchtmlreport/actions/workflows/lint.yml/badge.svg)](https://github.com/younke/asdf-xchtmlreport/actions/workflows/lint.yml)


[XCTestHTMLReport](https://github.com/XCTestHTMLReport/XCTestHTMLReport) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- swift 5.5+ toolchain as required by [XCTestHTMLReport](https://swiftpackageindex.com/XCTestHTMLReport/XCTestHTMLReport)

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
