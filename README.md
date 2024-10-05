# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

## Installs
Some things I had to install on Ubuntu to get things going:

### Apt Installs
```bash
sudo apt install python3-env
```

### `rust-analyzer`
I followed [these instructions](https://rust-analyzer.github.io/manual.html#rust-analyzer-language-server-binary) (but I put it in `~/.cargo/bin` since I already have that dir):
```bash
curl -L https://github.com/rust-lang/rust-analyzer/releases/latest/download/rust-analyzer-x86_64-unknown-linux-gnu.gz | gunzip -c - > ~/.cargo/bin/rust-analyzer
chmod +x ~/.cargo/bin/rust-analyzer
```
