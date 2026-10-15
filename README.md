# CNA Cemetery

This repository preserves projects moved out of
[CNA Lab](https://github.com/libcna/cna-lab). Each project is integrated as a
Git subtree with its complete source history; the imports are not squashed.

## Structure

### Bindings

Language bindings and their starter templates live under `bindings/`:

- `cna-common-lisp` and `cna-common-lisp-template`
- `cna-go` and `cna-go-template`
- `cna-java` and `cna-java-template`
- `cna-kotlin` and `cna-kotlin-template`
- `cna-python` and `cna-python-template`
- `cna-ruby` and `cna-ruby-template`
- `cna-rust` and `cna-rust-template`
- `cna-swift` and `cna-swift-template`
- `cna-ts` and `cna-ts-template`
- `cna-vbnet-template`

### Standalone projects

- `black-pine`
- `cna-studio`
- `explore-2d`
- `myra-cna`
- `tamagotchi-cna`

## Working with subtrees

To pull changes from a project's upstream repository while preserving its
history, use:

```bash
git subtree pull --prefix=<subtree-path> <remote-url> <branch>
```

Do not pass `--squash`: this repository intentionally retains the individual
source commits.
