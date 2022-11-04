# microbitv2

![https://tech.microbit.org/hardware/2-0-revision/](https://tech.microbit.org/docs/hardware/assets/microbit-overview-2.png)

---

## Pre-requisites

- cargo-embed
- cargo-binutils

```shell
cargo install cargo-embed cargo-binutils
```

Add the `thumbv7em-none-eabihf` toolchain to rustup

```shell
rustup target add thumbv7em-none-eabihf
```

### Optional

- arm-none-eabi-gdb (archlinux)

## Build & Flash

```shell
cargo embed
```