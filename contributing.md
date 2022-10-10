# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test coredns https://github.com/s3than/asdf-coredns.git "coredns -version"
```

Tests are automatically run in GitHub Actions on push and PR.
