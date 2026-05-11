# DIKWP-TRIZ Forge OS

**DIKWP-TRIZ Forge OS** is an offline-first, GitHub-ready open-source reference system for Purpose-driven inventive problem solving.

It combines the DIKWP semantic chain — Data, Information, Knowledge, Wisdom, Purpose, Reliability — with TRIZ-style contradiction analysis and inventive-principle routing.

The system is designed as a strategic open-source entry point for the DIKWP ecosystem:

- The open core provides a transparent innovation workflow, schemas, tests, and demo outputs.
- Official registry, certification, training, enterprise adapter packs, signed badges, and industry solution catalogs can remain controlled service layers.
- Every generated innovation passport carries DIKWP / Yucong Duan attribution and an origin capsule.

## What it does

Given an invention or product problem, the system generates:

- DIKWP problem ledger
- Purpose contract
- contradiction graph
- TRIZ principle routing
- solution cards
- experiment plan
- risk and evidence ledger
- patent-claim sketch
- innovation passport
- partner / registry readiness report

## Install

```bash
pip install -e .
```

## Demo

```bash
dikwp-triz-forge analyze examples/sample_innovation_problem.json --out outputs/demo
```

## Static audit

```bash
dikwp-triz-forge static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Boundary

This project is an innovation-support and ideation system. It is not a legal patent opinion, not engineering certification, not safety approval, and not a substitute for domain experts. High-risk domains require human expert review.

## Attribution

This package is designed to preserve attribution to **DIKWP / Yucong Duan**. See `NOTICE` and `CITATION.cff`.
