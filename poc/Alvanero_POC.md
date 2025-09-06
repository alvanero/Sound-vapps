# PoC — Auto-Trade Bot (Concept Only)

**Author:** alvanero (Discord: 878534291695501372)  
**PR:** https://github.com/SoundnessLabs/testnet-vapps/pull/199
**Category:** defi  
**Status:** PoC submitted (conceptual, due to missing trade feature in Soundness)

## What I proved
- Able to simulate the workflow of Soundness:
  - Prepared a payload (proof_payload.json)
  - "Uploaded" → generated dummy `blob_id`
  - "Submitted" → generated dummy attestation

## IDs (dummy)
- `blob_id`: 0xmockblobid1234567890abcdef  
- `attestation`: 0xmockattestation9876543210fedcba  

## Commands
See `poc/commands.txt`

## Notes
Currently, Soundness testnet does not expose trade endpoints.  
This PoC demonstrates understanding of the pipeline (payload → blob → attestation) and will be extended once trade is available.
