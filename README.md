# Portpicker-ipv4 - Pick a free unused IPV4 port

Forked from Portpicker-rs. The information for that is down below.
The API is the same but 


# Portpicker-rs - Pick a free unused port

[![Crates.io](https://img.shields.io/crates/v/portpicker)](https://crates.io/crates/portpicker)
[![Documentation](https://docs.rs/portpicker/badge.svg)](https://docs.rs/portpicker)

Picks a free port, that is unused on both TCP and UDP.

Usage:

```rust
portpicker::pick_unused_port().expect("No ports free")
```

## License

[The Unlicense](https://unlicense.org/): free to use, modify, and distribute.
