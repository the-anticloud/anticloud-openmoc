# Ethics — OPENMOC

**Project:** OPENMOC  
**Category:** NUCLEAR  
**Upstream:** https://github.com/mit-crpg/openmoc  
**Pinned commit:** `c9ac4e1ecc9c13bacb44fd470f7fce8c9355606f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8589479d03ceb745787e5bee75b60794e6c61931c4fec298e28f4bef9b44e331`  
**Date:** October 2026

## Position

OPENMOC is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
