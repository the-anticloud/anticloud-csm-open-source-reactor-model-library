# Reproduction

```
cd E:\fenta\Downloads\The Anticloud\ANTICLOUD_REPOS\NUCLEAR\CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY\anticloud
python tools\run_bench.py --out BENCH.json --quiet   # pass 1: generate BENCH.json (checks that cite it as evidence)
python tools\run_bench.py --out BENCH.json --quiet   # pass 2: record (deterministic re-run)
python tools\run_bench.py --out E:\fenta\Downloads\The Anticloud\ANTICLOUD_REPOS\NUCLEAR\CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY\ISOLATED_LAB_RESULTS\04_Evidence\16_checks_report.json
```

Exit code 0 only when all 16 checks PASS. The report JSON at the
--out path carries each check's own evidence object.

- BENCH.json SHA3-256: `e3f2d9d12ec2838eee7070568414b2f23a553596ba6fe50c0f46bae61ae3b9ad`
- Evidence report SHA3-256: `e3f2d9d12ec2838eee7070568414b2f23a553596ba6fe50c0f46bae61ae3b9ad`
- run_bench_output.txt SHA3-256: `40e216d6b28ee44f4333a78213b226bff726c75c2a2056c0fa6bc323fb1ed58f`
