# Contributing

After installing asdf, running below command in this repo finishes setups.

```console
$ asdf plugin-add yamlfmt https://github.com/kachick/asdf-yamlfmt.git
$ asdf install yamlfmt
$ makers setup
...
```

`help` shows providing tasks for developping

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
