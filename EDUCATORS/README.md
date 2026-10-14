# Educators — CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY

**Project:** CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY  
**Category:** NUCLEAR  
**Upstream:** https://github.com/khurrumsaleem/CSM-Open-source-Reactor-Model-Library  
**Pinned commit:** `ad26ab4a038f347e7b622e8e7ae084975e8be6e9`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `89534afa9640d4b8444ff3a5380bac2ac8ec9fb07c53c1619e4bdf7cf8d80a1b`  
**Date:** October 2026

## Teaching with CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `89534afa9640d4b8444ff3a5380bac2ac8ec9fb07c53c1619e4bdf7cf8d80a1b` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
