# nectere

[![crates.io](https://img.shields.io/crates/v/nectere.svg)](https://crates.io/crates/nectere)
[![docs.rs](https://docs.rs/nectere/badge.svg)](https://docs.rs/nectere)
[![license](https://img.shields.io/crates/l/nectere.svg)](https://crates.io/crates/nectere)

[![clippy](https://github.com/scattered-systems/nectere/nectere/actions/workflows/clippy.yml/badge.svg)](https://github.com/scattered-systems/nectere/nectere/actions/workflows/clippy.yml)
[![rust](https://github.com/scattered-systems/nectere/nectere/actions/workflows/rust.yml/badge.svg)](https://github.com/scattered-systems/nectere/nectere/actions/workflows/rust.yml)

***

_**The library is currently in the early stages of development and is not yet ready for production use.**_

An efficient space for mananging any and all bindings

## Features

- [x] Feature 1

## Getting Started

### Building from the source

Start by cloning the repository

```bash
git clone https://github.com/scattered-systems/nectere/nectere.git
cd nectere
```

#### _Building the project_

```bash
cargo build --all-features -r -v --workspace
```

#### _Running tests_

```bash
cargo test --all-features -r -v --workspace
```

## Usage

Add this to your `Cargo.toml`:

```toml
[dependencies.nectere]
features = []
version = "0.0.0"
```

### Examples

#### _Basic Usage_

```rust
    extern crate nectere;

    fn main() -> Result<(), Box<dyn std::error::Error>> {
        tracing_subscriber::fmt::init();
        tracing::info!("Welcome to {name}", name = nectere);


        Ok(())
    }
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
