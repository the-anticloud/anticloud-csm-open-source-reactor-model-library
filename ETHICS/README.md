# Ethics — CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY

**Project:** CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY  
**Category:** NUCLEAR  
**Upstream:** https://github.com/khurrumsaleem/CSM-Open-source-Reactor-Model-Library  
**Pinned commit:** `ad26ab4a038f347e7b622e8e7ae084975e8be6e9`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `89534afa9640d4b8444ff3a5380bac2ac8ec9fb07c53c1619e4bdf7cf8d80a1b`  
**Date:** October 2026

## Position

CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY is packaged for offline deployment with a verifiable audit trail. The
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
