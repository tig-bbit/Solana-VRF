# Orao Solana VRF SDKs

This repository provides off-chain Rust and JS web3 SDKs for requesting on-chain
randomness using ORAO VRF contract.

Browse through `js` and `rust` subdirectories for more info.

### How to run a test validator.

Note that `anchor test` will run it for the [cpi](rust/examples/cpi) tests.

Here is an example:

```sh
solana-test-validator -r \
    --bpf-program VRFzZoJdhFWL8rkvu87LpKM3RbcVezpMEc6X5GVDr7y js/dist/orao_vrf.so \
    --ledger /tmp/test-ledger
```
