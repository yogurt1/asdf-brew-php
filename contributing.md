# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test brew-php https://github.com/yogurt1/asdf-brew-php.git "php --version"
```

Tests are automatically run in GitHub Actions on push and PR.
