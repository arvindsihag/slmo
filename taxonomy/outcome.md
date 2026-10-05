# Outcome (O)

**Definition.** The operational consequence that followed the failure.

Explicit outcomes prevent unlike events — for example, a recoverable
navigation fault and a discontinued pilot — from being treated as
equivalent.

## Values

| Outcome | Description |
|---|---|
| Task interruption | The nominal task could not be completed |
| Human intervention | A person had to step in to restore operation |
| Degraded service | The service continued but at reduced quality |
| Trust reduction | Users reported or exhibited reduced trust |
| Reduced adoption | Initial interest did not translate into sustained use |
| Abandonment / decommissioning | The deployment was discontinued |
| Safety incident | A person or property was put at risk |
| Failure to scale | The pilot did not extend to further sites or tasks |

## Why outcome matters

Outcome is the observable signal. It is what a deployment review
actually sees. Recording it explicitly makes the case comparable
across domains and prevents heterogeneous events from being collapsed
into a single "failure score".

## Examples from the paper

- **Robo-Barista** — reduced repeat use
- **Henn-na Hotel** — human intervention, degraded service
- **Lindsey** — human intervention (recoverable)
- **Blue Jay** — discontinuation in operations

See [`../cases/`](../cases/README.md) for full encodings.

## Related files

- [Stage](stage.md)
- [Locus](locus.md)
- [Mechanism](mechanism.md)
- [Taxonomy overview](README.md)
