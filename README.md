# thumbor4rust
an imaging service which enables crop, resizing and flipping of images.

## dependencies
please see Cargo.toml

## Usage
1. open src/engine/photon.rs, substitute ${local_picture} with a real path of picture;
1. cargo build --release;
2. RUST_LOG=info target/release/thumbor