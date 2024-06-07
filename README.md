# SSD1309 driver

[![SSD1309 display module showing the Rust logo](readme_banner.jpg?raw=true)](examples/image.rs)

I2C/SPI driver for the SSD1309 OLED display written in 100% Rust.

Heavily based off of the [`SH1106 driver`](https://github.com/jamwaffles/sh1106) by @jamwaffles.

## Implementation note

It's important to use correct reset logic for the SSD1309, unlike with some other display drivers.
The `GraphicsMode::reset` method is a good way to ensure this is accomplished.

## Usage

Check the [documentation](https://docs.rs/ssd1309) and [examples](examples/).

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  <http://www.apache.org/licenses/LICENSE-2.0>)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.
