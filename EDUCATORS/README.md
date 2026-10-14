# Educators — IVERILOG

**Project:** IVERILOG  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `e64f247bf19da8d2d694484e758b07f6911aa455`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f44daa7a7af1287f235702f8065e3c0c42c868e50fc0cb4e552ddf2b1720cca6`  
**Date:** October 2026

## Teaching with IVERILOG

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f44daa7a7af1287f235702f8065e3c0c42c868e50fc0cb4e552ddf2b1720cca6` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
