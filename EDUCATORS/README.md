# Educators — OPENMOC

**Project:** OPENMOC  
**Category:** NUCLEAR  
**Upstream:** https://github.com/mit-crpg/openmoc  
**Pinned commit:** `c9ac4e1ecc9c13bacb44fd470f7fce8c9355606f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8589479d03ceb745787e5bee75b60794e6c61931c4fec298e28f4bef9b44e331`  
**Date:** October 2026

## Teaching with OPENMOC

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `8589479d03ceb745787e5bee75b60794e6c61931c4fec298e28f4bef9b44e331` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
