# Homebrew tap for bkt

This tap publishes the Homebrew formula for [`bkt`](https://github.com/cryptekbits/bbCLI), a Rust Bitbucket CLI.

The formula is generated from GitHub Release artifacts by the `bbCLI` release workflow after each tagged release.

## Install

```bash
brew tap manan-ramnani/tap
brew install bitbucket-cli
```

## Maintainer Notes

- Do not hand-edit checksums unless repairing a failed release.
- The source release artifacts live in `https://github.com/cryptekbits/bbCLI/releases`.
- The expected formula path is `Formula/bitbucket-cli.rb`.
