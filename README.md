# SLMO: A Deployment Failure Taxonomy for Robot Systems

Companion repository for the HRI 2027 Industry White Paper:

> **When Robot Deployments Fail: A Practitioner's Taxonomy**

This repository provides the diagnostic framework, case encodings, and
deployment-readiness checklist described in the paper. It is intended
for practitioners reviewing pilots, planning deployments, conducting
post-incident reviews, and deciding whether to scale.

## The SLMO Representation

A deployment failure is represented as

    F = <S, L, M, O>

where:

- **S — Stage**: when the problem emerges in the deployment lifecycle
- **L — Locus**: where the failure is located
- **M — Mechanism**: why it arises
- **O — Outcome**: what operational consequence follows

Multiple labels may be assigned because real deployments usually
involve interacting causes rather than a single isolated fault.

## Contents

| Folder | Description |
|---|---|
| [`taxonomy/`](taxonomy/README.md) | Full definitions of Stage, Locus, Mechanism, Outcome |
| [`cases/`](cases/README.md) | Encoded failure cases from the paper |
| [`checklist/`](checklist/deployment-readiness.md) | Eight deployment-readiness questions |
| `coding-sheet.csv` | Cross-case evidence table |

## Quick start

1. Read [`taxonomy/README.md`](taxonomy/README.md) for the four dimensions.
2. Review [`cases/`](cases/README.md) for worked encodings.
3. Apply [`checklist/deployment-readiness.md`](checklist/deployment-readiness.md) to your own deployment.

## Citation

If you use this framework, please cite the paper. See [`CITATION.cff`](CITATION.cff).

## License

Documentation is released under CC-BY-4.0. See [`LICENSE`](LICENSE).
