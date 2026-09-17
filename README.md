# ploy-cli

Public release artifacts for the Ploy macOS Agent and CLI.

This repository intentionally contains no Agent source code. The trusted
source, tests, and packaging workflow live in
[`ZainCheung/ploy`](https://github.com/ZainCheung/ploy); tagged builds publish
the packaged artifact here as GitHub Releases. Homebrew metadata is maintained
separately in [`ZainCheung/homebrew-tap`](https://github.com/ZainCheung/homebrew-tap).

## Install

```sh
brew install ZainCheung/tap/ploy
ploy version
```

Upgrade an existing installation with:

```sh
brew upgrade ploy
```

Normal onboarding remains:

```sh
ploy connect preg_xxx
```
