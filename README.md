# wasm-vm-executor-rs

VM wasmer 2.2 executor + specialized C API to be used from Go.

Call `make capi` in the root to get the binary and the C header.

////
1) add home = "=0.5.9" at vm-executor-wasmer->Cargo.toml->dependencies
2) delete rust-toolchain.toml file (because it always overrides the rustc version to 1.83.0 stable, but we have to work with 1.77.2)
3) rustup install 1.77.2
rustup override set 1.77.2
////
