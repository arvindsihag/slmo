# The SLMO Taxonomy

The taxonomy represents a deployment failure as a four-part
diagnostic tuple:

    F = <S, L, M, O>

The four dimensions are:

- [Stage (S)](stage.md) — *when* the problem emerges
- [Locus (L)](locus.md) — *where* the failure is located
- [Mechanism (M)](mechanism.md) — *why* it arises
- [Outcome (O)](outcome.md) — *what operational consequence follows*

## Why four dimensions?

Existing frameworks characterise robot failures, trust-relevant
failures, HRI context, accident mechanisms, and service-design
failures from complementary perspectives. The SLMO representation
connects these concerns to the operational lifecycle and to
observable deployment outcomes, so that a practitioner can trace
*what happened* back to *where and why it happened*.

## Using the taxonomy

To encode a deployment event:

1. Identify the **stage** at which the problem first became visible.
2. Assign one or more **loci** that describe where the failure sits.
3. Assign one or more **mechanisms** that explain why it arose.
4. Record the **operational outcome** that followed.

Multiple labels per dimension are expected. For example:

    <sustained operation,
     human/workflow,
     capability-expectation mismatch,
     human intervention/degraded service>

This event is not a generic "robot failure". It is a specific
diagnosis that points to service allocation, interface design, or
escalation process as the corrective target.

## Related files

- [Stage](stage.md)
- [Locus](locus.md)
- [Mechanism](mechanism.md)
- [Outcome](outcome.md)
- [Cases](../cases/README.md)
- [Checklist](../checklist/deployment-readiness.md)
