# Blinky

This program leverages the rp-hal crate to blink an LED on the Raspberry Pi Pico.

### Notes to self
Requires the `memory.x` file to specify the memory layout of the Pico.
See ./cargo/config for more details

### Build
```bash
  cargo build --release
```

### Flash
Hold the BOOTSEL button while plugging in the Pico to the USB port.
```bash
  cargo run --release
```