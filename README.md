# rp_pico_template
Template for developing Raspberry Pi Pico in Rust.

## How to use

1. Clone this repository.

```shell
git clone http://github.com/doraneko94/rp_pico_template
```

2. Rename this directory.

3. Edit `Cargo.toml`.

```text
[package]
name = "rp_pico_template" -> "your project name"
```

4. Continue to write your code in `lib.rs` or bin files.

## How to use blinky example

1. Connect your `Raspberry Pi Pico` to your computer with pushing the white button (`BOOTSEL`) on board.

2. Run `led.rs`

```shell
cargo run --release --bin led
```