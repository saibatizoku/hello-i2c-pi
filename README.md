Start/Stop a blinking LED on an I2C slave
=========================================

Simple example written in [Rust](https://www.rust-lang.org), cross-compiled to run on a Raspberry Pi with ARMv6 architecture, and successfully connected to an Arduino programmed with [arduino-i2c-slave-blinker](https://github.com/saibatizoku/arduino-i2c-slave-blinker).

To run, clone this repository and build/run with cargo.

To turn on the blinking:

```
cargo run on
```


To turn off the blinking:

```
cargo run off
```

This example was tested on a Raspberry Pi with I2C enabled.
