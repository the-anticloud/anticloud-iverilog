# Ethics — IVERILOG

**Project:** IVERILOG  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `e64f247bf19da8d2d694484e758b07f6911aa455`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f44daa7a7af1287f235702f8065e3c0c42c868e50fc0cb4e552ddf2b1720cca6`  
**Date:** October 2026

## Position

IVERILOG is packaged for offline deployment with a verifiable audit trail. The
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
