## Patched ed25519-consensus for RISC Zero

This repository adapts the `ed25519-consensus` to the RISC Zero patched version of curve25519-dalek, 
while the original version requires curve25519-dalek-ng. 

This is inspired by Succinct's patch for SP1, which uses this toward a benchmark regarding Tendermint signatures.

All credits go to the original author of `ed25519-consensus`, [Henry de Valence](https://hdevalence.ca/) 
as well as his team at [Penumbra](https://penumbra.zone/).