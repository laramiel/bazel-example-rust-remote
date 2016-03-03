# bazel-example-rust-remote

An example project demonstrating bazel build rules for rust.
This repository only contains a remote library, with build
rules already included.

This requires bazel release > `bazel-0.20`.

This example can be compiled without bazel using:
```
rustc --crate-type=lib remote.rs
```
