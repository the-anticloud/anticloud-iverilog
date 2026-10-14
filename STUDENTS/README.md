# Students — IVERILOG

**Project:** IVERILOG  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `e64f247bf19da8d2d694484e758b07f6911aa455`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f44daa7a7af1287f235702f8065e3c0c42c868e50fc0cb4e552ddf2b1720cca6`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e64f247bf19da8d2d694484e758b07f6911aa455`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f44daa7a7af1287f235702f8065e3c0c42c868e50fc0cb4e552ddf2b1720cca6`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
