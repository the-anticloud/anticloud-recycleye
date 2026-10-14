# Educators — RECYCLEYE

**Project:** RECYCLEYE  
**Category:** WASTE_MANAGEMENT  
**Upstream:** https://github.com/pgredigui/recycleye  
**Pinned commit:** `1bf9ec1a68cfbf5fb148bda5ce737fa38029b61b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7d5fb7782e43b008bd56d274b354b6865d409b2da76e0b3cdcb81c8fb718ceec`  
**Date:** October 2026

## Teaching with RECYCLEYE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `7d5fb7782e43b008bd56d274b354b6865d409b2da76e0b3cdcb81c8fb718ceec` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
