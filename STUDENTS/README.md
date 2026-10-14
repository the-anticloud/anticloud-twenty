# Students — TWENTY

**Project:** TWENTY  
**Category:** CONSULTANCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `a7b4057817bb098f554c5626a19c3d5ae14b280b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `35625107f64d207a408c17322dab5f3e01f35ec04455039f87c53fa40c391524`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `a7b4057817bb098f554c5626a19c3d5ae14b280b`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `35625107f64d207a408c17322dab5f3e01f35ec04455039f87c53fa40c391524`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
