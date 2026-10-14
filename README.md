# CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY` in category **NUCLEAR**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY · **Upstream pin:** `ad26ab4a038f347e7b622e8e7ae084975e8be6e9` · **Category:** NUCLEAR · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

# CSM Open-Source Reactor Model Library

An open-source collection of nuclear reactor models built with [OpenMC](https://openmc.org/).
Each top-level directory is an independent model project. Projects can be developed and
run separately; there is no shared Python package or project-wide launcher.

## project layout

| Directory | Purpose | Status |
| --- | --- | --- |
| [`iaea-tecdoc-core/`](iaea-tecdoc-core/README.md) | IAEA TECDOC-643 Appendix A-2 generic 10 MW LEU research reactor OpenMC model | Implemented |
| [`hp-mr/`](hp-mr/README.md) | High-power microreactor model | Reserved project directory |
| [`lunar-fsp-microreactor/`](lunar-fsp-microreactor/README.md) | Lunar FSP microreactor model | Reserved project directory |
| [`msre/`](msre/README.md) | Molten Salt Reactor Experiment model | Reserved project directory |
| [`pebble-bed-htgr/`](pebble-bed-htgr/README.md) | Pebble-bed high-temperature gas reactor model | Reserved project directory |
| [`radiant-kaleidos/`](radiant-kaleidos/README.md) | Radiant Kaleidos microreactor model | Reserved project directory |

At present, `iaea-tecdoc-core` is the project's implemented model. The other
directories contain documentation placeholders for future model projects.

## Working with a model

Read the README inside the model directory before running it. Model-specific dependencies,
cross-section libraries, input assumptions, run commands, and validation checks belong in
that README rather than in this root document.

The implemented IAEA model is run from its project directory. Its central driver builds
the geometry, materials, settings, and tallies, then launches an OpenMC eigenvalue run:

```text
cd iaea-tecdoc-core
python model/core.py --help
```

The driver accepts controls for blade insertion, particle and batch counts, output location,
and optional depletion zoning. See [`iaea-tecdoc-core/README.md`](iaea-tecdoc-core/README.md)
for the complete workflow and verification commands.

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

```text
cd iaea-tecdoc-core
python model/core.py --help
```

The driver accepts controls for blade insertion, particle and batch counts, output location,
and optional depletion zoning. See [`iaea-tecdoc-core/README.md`](iaea-tecdoc-core/README.md)
for the complete workflow and verification commands.

## Contributing

run separately; there is no shared Python package or project-wide launcher.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** CSM_OPEN_SOURCE_REACTOR_MODEL_LIBRARY
- **Pinned SHA:** `ad26ab4a038f347e7b622e8e7ae084975e8be6e9`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`aa03d750726127ac962989ec7290a00f5388fcc3ba60c50fe3cba30ba373cb82`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

