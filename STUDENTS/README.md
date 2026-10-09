# Students — OPENMOC

**Project:** OPENMOC  
**Category:** NUCLEAR  
**Upstream:** https://github.com/mit-crpg/openmoc  
**Pinned commit:** `c9ac4e1ecc9c13bacb44fd470f7fce8c9355606f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8589479d03ceb745787e5bee75b60794e6c61931c4fec298e28f4bef9b44e331`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `c9ac4e1ecc9c13bacb44fd470f7fce8c9355606f`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `8589479d03ceb745787e5bee75b60794e6c61931c4fec298e28f4bef9b44e331`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
