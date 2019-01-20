# docker-rust-wasm

This is a container image with Rust and WebAssembly. The intention is to be able to build any
of the [wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) examples using it.

```sh
cargo build --target wasm32-unknown-unknown
wasm-bindgen target/wasm32-unknown-unknown/debug/foo.wasm --out-dir .
```

For examples see [Hello, Rust!](https://www.hellorust.com/) or the
[Rust/WebAssembly WG](https://rustwasm.github.io/) page.
