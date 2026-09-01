# CodeGrapher Homebrew tap

Homebrew tap for [CodeGrapher](https://github.com/code-grapher/codegrapher)
command-line tools.

## Install

```sh
brew install code-grapher/tap/codegrapher
```

Or tap first, then install:

```sh
brew tap code-grapher/tap
brew install codegrapher
```

## Contents

Casks are published automatically by
[`code-grapher/codegrapher`](https://github.com/code-grapher/codegrapher)'s
release workflow via GoReleaser. Do not edit `Casks/*.rb` by hand — a release
will overwrite it.

The published binaries are signed and notarized with an Apple Developer ID, and
the release pipeline verifies `codesign --verify --deep --strict` against the
real published artifact before promoting a release out of draft.
