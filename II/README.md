# Independent Insurance — OPENMOC

**Project:** OPENMOC  
**Category:** NUCLEAR  
**Upstream:** https://github.com/mit-crpg/openmoc  
**Pinned commit:** `c9ac4e1ecc9c13bacb44fd470f7fce8c9355606f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8589479d03ceb745787e5bee75b60794e6c61931c4fec298e28f4bef9b44e331`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | OPENMOC with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `8589479d03ceb745787e5bee75b60794e6c61931c4fec298e28f4bef9b44e331`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
