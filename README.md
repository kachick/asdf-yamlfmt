# asdf-yamlfmt

[![Build](https://github.com/kachick/asdf-yamlfmt/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/kachick/asdf-yamlfmt/actions/workflows/build.yml?query=branch%3Amain) [![Lint](https://github.com/kachick/asdf-yamlfmt/actions/workflows/lint.yml/badge.svg?branch=main)](https://github.com/kachick/asdf-yamlfmt/actions/workflows/lint.yml?query=branch%3Amain) [![rtx](https://github.com/kachick/asdf-yamlfmt/actions/workflows/rtx.yml/badge.svg?branch=main)](https://github.com/kachick/asdf-yamlfmt/actions/workflows/rtx.yml?query=branch%3Amain)

[yamlfmt](https://github.com/google/yamlfmt/) plugin for the [asdf version manager](https://asdf-vm.com).\
Tested also [rtx](https://github.com/jdxcode/rtx).

## Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

## Install

Plugin:

```shell
asdf plugin add yamlfmt https://github.com/kachick/asdf-yamlfmt.git
```

[short-name is also available](https://github.com/asdf-vm/asdf-plugins/blob/42ef3772359cb2142e357508706acacf44fddf10/plugins/yamlfmt#L1) if you turn off [disable_plugin_short_name_repository](https://asdf-vm.com/manage/configuration.html#disable-plugin-short-name-repository)

```shell
asdf plugin add asdf-yamlfmt
```

yamlfmt:

```shell
# Show all installable versions
asdf list-all yamlfmt

# Install specific version
asdf install yamlfmt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yamlfmt latest

yamlfmt -help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

## Contributing

Contributions of any kind welcome! See the [contributing guide](CONTRIBUTING.md).

## License

See [LICENSE](LICENSE) © [Kenichi Kamiya](https://github.com/kachick/)
