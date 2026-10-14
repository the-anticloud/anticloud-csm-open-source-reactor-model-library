# Students — CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY

**Project:** CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY  
**Category:** NUCLEAR  
**Upstream:** https://github.com/khurrumsaleem/CSM-Open-source-Reactor-Model-Library  
**Pinned commit:** `ad26ab4a038f347e7b622e8e7ae084975e8be6e9`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `89534afa9640d4b8444ff3a5380bac2ac8ec9fb07c53c1619e4bdf7cf8d80a1b`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ad26ab4a038f347e7b622e8e7ae084975e8be6e9`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `89534afa9640d4b8444ff3a5380bac2ac8ec9fb07c53c1619e4bdf7cf8d80a1b`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
