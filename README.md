# DALI FLPR Engine Blobs

This repository publishes prebuilt FLPR DALI engine archives for the
`nrf54l15/cpuflpr` target.

## Purpose

These archives are consumed by the
[`dali-nrf54`](https://github.com/Borissimus/dali-nrf54) module.

This repository distributes release assets only. DALI engine source code is
maintained separately.

## Release assets

Each release publishes these archives:

- `libdali_flpr_engine_release.a`
- `libdali_flpr_engine_debug.a`

## Compatibility

The archives are built for:

- SoC target: `nrf54l15/cpuflpr`
- Zephyr SDK: `0.16.8`

Consumers should treat each release as tied to the toolchain and integration
state it was built against.
