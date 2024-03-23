# Contributing

Maintaining this repository assumes that you are not using old versions of bash such as 3.x, which is included in MacOS\
I recommend using the [Nix package manager](https://nixos.org/) to prepare base environments.\
This repository contains the [flake.nix](flake.nix).

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
