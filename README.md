# libbf-rs

Inspired by the [libbf] C library.

## Vision

A simple pure-rust implementation of truly arbitrary precision floating point arithmetic that is competitive with `libbf` at all scales. `libbf-rs` is intended to be used in embedded applications: Crate feature flags provide `nostd` library comparable in binary size to `libbf`.

`libbf-rs` is usable on `rust` stable channel.


[libbf]: https://bellard.org/libbf/
