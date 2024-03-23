# Contributing

After installing asdf, running below command in this repo finishes setups.

```console
$ asdf plugin-add asdf-cargo-make https://github.com/kachick/asdf-cargo-make.git
$ asdf install cargo-make
$ makers setup
...
```

`help` shows providing tasks for developing

```console
$ makers help
check - Should pass before merging PR
...
```

`check` task should be passed after your commits

```console
$ makers check
...
```
