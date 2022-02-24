# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test xchtmlreport https://github.com/younke/asdf-xchtmlreport.git "xchtmlreport -h"
```

Tests are automatically run in GitHub Actions on push and PR.
