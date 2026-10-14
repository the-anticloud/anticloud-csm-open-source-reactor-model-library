# Command Line Interface — CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY

**Upstream:** https://github.com/khurrumsaleem/CSM-Open-source-Reactor-Model-Library

## Anticloud CLI

```bash
# Install
pip install anticloud-csm-open-source-reactor-model-library

# Run offline with PAX inference
anticloud-csm-open-source-reactor-model-library --offline --pax-local

# Run with AIOSS logging
anticloud-csm-open-source-reactor-model-library --aioss-log ./ledger.jsonl

# Single binary (after build)
./csm_open_source_reactor_model_library --config config.yaml
```

## Options

| Flag | Description |
| --- | --- |
| `--offline` | Disable all network calls |
| `--pax-local` | Use local PAX inference at 127.0.0.1:11434 |
| `--aioss-log PATH` | Write AIOSS audit chain to PATH |
| `--encrypt` | Enable AES-256 at rest for output files |
| `--gpu` | Force GPU inference |
| `--cpu` | Force CPU inference |
| `--config PATH` | Load configuration from YAML file |
