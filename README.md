# This Repository Is Deprecated

This library has been renamed and moved to [ssvm_storage_interface](https://github.com/second-state/ssvm_storage_interface).
Please follow the resulting [new ssvm_storage_interface crate](https://crates.io/crates/ssvm_storage_interface) for further development.
No further development will take place in this repository.

# Rust Storage Interface Library

A Rust library that provides Rust to WebAssembly developers with syntax for "load" & "store" functionality for their data when their Wasm is being executed on SecondState's SSVM.

From a high-level overview here, we are essentially building a storage interface that will allow the native operating system (which SSVM is running on) to play a part in the runtime execution. Specifically, play a part in facilitating the storing and loading of data as part of Wasm execution. 

# How to use this library

Please see the [official specification for this storage interface](https://github.com/second-state/specs/blob/master/storage_interface.md) for more information.

# Crates.io

The official crate is available at [crates.io](https://crates.io/crates/rust_storage_interface_library)