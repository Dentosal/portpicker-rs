# Portpicker-rs - Pick a free unused port

Picks a free port, that is unused on both TCP and UDP.

Usage:

```rust
portpicker::pick_free_port().expect("No ports free")
```