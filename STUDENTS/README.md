# Students — RECYCLEYE

**Project:** RECYCLEYE  
**Category:** WASTE_MANAGEMENT  
**Upstream:** https://github.com/pgredigui/recycleye  
**Pinned commit:** `1bf9ec1a68cfbf5fb148bda5ce737fa38029b61b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7d5fb7782e43b008bd56d274b354b6865d409b2da76e0b3cdcb81c8fb718ceec`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `1bf9ec1a68cfbf5fb148bda5ce737fa38029b61b`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `7d5fb7782e43b008bd56d274b354b6865d409b2da76e0b3cdcb81c8fb718ceec`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
