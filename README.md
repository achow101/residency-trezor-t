# Chaincode Residency Trezor T Images

This repo contains 14 images for the Trezor T emulator to be used for the harware wallet and PSBT session.

## Usage

Build the Trezor T emulator according to https://github.com/trezor/trezor-firmware/blob/master/core/docs/build/emulator.md

To use the `n`th image, do:

```
env TREZOR_PROFILE=path/to/images/t<n>/ ./emu.sh
```

For example, to use `t8` from within the `trezor-firmware/core` directory, do:

```
env TREZOR_PROFILE=../trezor-t-images/t8/ ./emu.sh
```

HWI will be able to connect to and interact with the emulator.

## Block height

Coins sent after testnet block 1543210.
