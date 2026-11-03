# Kovallent Homebrew tap

```bash
brew install kovallent/tap/kv-cli
```

[kv-cli](https://github.com/kovallent/kv-cli) enforces parameter contracts across Python data pipelines: required parameters such as `target_environment`, hardcoded credentials, and infrastructure pinned to one environment. It runs locally, with no account and no network call.

The formula installs the prebuilt release binary for macOS (Apple silicon and Intel) and Linux (x86-64 and ARM64). It doesn't need a Rust toolchain.

```bash
brew upgrade kv-cli      # after a new release
brew uninstall kv-cli
```

`Formula/kv-cli.rb` is written by kv-cli's release workflow after each release. Changes to the formula belong in [`packaging/homebrew/formula.sh`](https://github.com/kovallent/kv-cli/blob/main/packaging/homebrew/formula.sh), not here.
