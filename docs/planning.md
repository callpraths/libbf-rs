Inspiration: [libbf C library](https://bellard.org/libbf/)

## Vision

A simple pure-rust implementation of truly arbitrary precision floating point arithmetic that is 
competitive with `libbf` at all scales. `libbf-rs` is intended to be used in embedded applications: 
Crate feature flags provide `nostd` library comparable in binary size to `libbf`.

`libbf-rs` is usable on `rust` stable channel.

## Plan

* Study `libbf`: Add sections below
  * Sketch code
  * Identify key algorithms
  * Study key algorithms
* Study `rust` API: Add sections below
  * Study prior art crates to learn from their API choices
  * Look at Rust num crate for interop
  * Look at standard Rust traits for numerics
  * Look at Serde
  
...

## Prior art

* Production ready: [rug - Rust][crate-rug]
  * Wraps the most widely used C library.
* [alkis/decimal: Decimal Floating Point arithmetic for rust][crate-decimal]
  * Wraps a C library. Not arbitrary precision
* [paupino/rust-decimal: A Decimal Implementation written in pure Rust suitable for financial calculations][crate-rust-decimal]
  * Well maintained, large list of contributors
  * Pure rust
  * Intended for financial calculations; Rounding strategies are specific to financial calculations
  * Not arbitrary precision
* [akubera/bigdecimal-rs: Arbitrary precision decimal crate for Rust][crate-bigdecimal-rs]
  * Not _really_ arbitrary precision
  * Interoperates with the widely used num crate.
* [huonw/float: Arbitrary precision floating point in Rust][crate-float]
  * Incomplete / not updated in years


[crate-bigdecimal-rs]: https://github.com/akubera/bigdecimal-rs
[crate-decimal]: https://github.com/alkis/decimal
[crate-float]: https://github.com/huonw/float
[crate-rug]: https://docs.rs/rug/0.6.0/rug/
[crate-rust-decimal]: https://github.com/paupino/rust-decimal

