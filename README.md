# ploy-cli

Public release artifacts for the Ploy macOS Agent and CLI.

This repository intentionally contains no Agent source code. It is the public
release surface for Ploy; tagged builds from the trusted source repository
publish packaged artifacts here as GitHub Releases. Homebrew metadata is
maintained separately in
[`ZainCheung/homebrew-tap`](https://github.com/ZainCheung/homebrew-tap).

The source repository is kept separate from this public release repository;
users only need the install and connect commands below.

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

The published `v0.1.0` bundle is the one-time bootstrap release created
before the trusted source tag workflow was enabled. The first workflow-driven
source release is expected to be `v0.1.1` or later; Homebrew metadata is updated
only after that release asset and its checksum are verified.
