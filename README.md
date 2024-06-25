# Baby liminal

This repository is a collection of Rust crates that were used to implement PoC of Liminal on Aleph Zero (L1) blockchain.
This includes:
- [`baby-liminal-extension`](./baby-liminal-extension): chain extension component (Smart Contract <-> Runtime communication for halo2 zkSNARK verification)
- [`aleph-runtime-interfaces`](./runtime-interfaces): runtime interface component for outsourcing proof verification from runtime to host
- [`pallet-feature-control`](./pallets/feature-control): runtime pallet for enabling/disabling proof verification feature in runtime
- [`pallet-vk-storage`](./pallets/vk-storage): runtime pallet for storing verification keys
