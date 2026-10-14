# Educators — TWENTY

**Project:** TWENTY  
**Category:** CONSULTANCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `a7b4057817bb098f554c5626a19c3d5ae14b280b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `35625107f64d207a408c17322dab5f3e01f35ec04455039f87c53fa40c391524`  
**Date:** October 2026

## Teaching with TWENTY

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `35625107f64d207a408c17322dab5f3e01f35ec04455039f87c53fa40c391524` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
