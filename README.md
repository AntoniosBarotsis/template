# Rust Github Template

A template for [cargo generate](https://github.com/cargo-generate/cargo-generate) that aims to be a starting point suitable for
the vast majority of rust projects that will be hosted on GitHub.

See the project [website](https://rust-github.github.io).

## Changes in this fork

- Added the [`config.toml`](./template/.cargo/config.toml) and
  [`rustfmt.toml`](./template/rustfmt.toml) I usually use
- Switched to a [GPL 3](./template/LICENSE) license

## Usage

Here are my configs:

```toml
# ~/.cargo/cargo-generate.toml
[favorites.demo]
git = "https://github.com/AntoniosBarotsis/template"
vcs = "Git"
init = false
overwrite = true

# ~/.cargo/config.toml
[alias]
gen = "generate demo"
```

Usage: `cargo gen`
