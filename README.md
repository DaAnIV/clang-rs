clang-rs
========

[![crates.io](https://img.shields.io/crates/v/clang.svg)](https://crates.io/crates/clang)
[![Travis CI](https://travis-ci.org/KyleMayes/clang-rs.svg?branch=master)](https://travis-ci.org/KyleMayes/clang-rs)

An idiomatic Rust wrapper for libclang.

Supported on the stable, beta, and nightly Rust channels.

Released under the MIT license.

### Dependencies

This crate depends on `libclang.dll` (Windows), `libclang.so` (Linux), or `libclang.dylib` (OS X).
These binaries can be either be installed as a part of Clang or downloaded
[here](http://llvm.org/releases/download.html).

The `libclang` binary will be looked for in likely places (e.g., `/usr/lib` on Linux), but you can
specify the directory the `libclang` binary is in with the `LIBCLANG_PATH` environment variable.

### Supported Versions

* 3.5.x - [Documentation](https://kylemayes.github.io/clang-rs/3_5/clang)
* 3.6.x - [Documentation](https://kylemayes.github.io/clang-rs/3_6/clang)
* 3.7.x - [Documentation](https://kylemayes.github.io/clang-rs/3_7/clang)
* 3.8.x - [Documentation](https://kylemayes.github.io/clang-rs/3_8/clang)

If you do not select a specific version, a common subset API will be availabile. The documentation
for this API is [here](https://kylemayes.github.io/clang-rs/all/clang).
