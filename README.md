# Portpicker-rs - Pick a free unused port

Picks a free port, that is unused on both TCP and UDP.

Usage:

```rust
let port: u16 = pick_unused_port().expect("No ports free");
```