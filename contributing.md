# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test cloud-provider-kind https://github.com/farkasmate/asdf-cloud-provider-kind.git "cloud-provider-kind --help"
```

Tests are automatically run in GitHub Actions on push and PR.
