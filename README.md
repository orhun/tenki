# Tenki

tty-clock with weather effect written by Rust and powerd by [ratatui](https://github.com/ratatui-org/ratatui)

![demo](./doc/demo.gif)

## Installation

### Install from Source Code

tenki is written in Rust, so you'll need to grab a [Rust installation](https://www.rust-lang.org/) in order to compile it.

```shell
git clone https://github.com/ckaznable/tenki
cd tenki
make build
sudo make install
```

If you want to uninstall

```shell
sudo make uninsall
```

## Usage

```
Usage: tenki [OPTIONS]

Options:
      --mode <MODE>  [default: rain] [possible values: rain, snow]
      --fps <FPS>    [default: 30] 1-60
  -h, --help         Print help
  -V, --version      Print version
```

## Roadmap

- [x] CLI options
- [ ] customizable

## LICENSE

[MIT](./LICENSE)

