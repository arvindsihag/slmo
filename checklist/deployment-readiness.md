# Deployment-Readiness Checklist

Eight questions for pilot reviews, readiness assessments,
post-incident reflection, and pilot-to-scale decisions. Apply before
launch and revisit during pilot operation and scaling.

## 1. Capability

Which real operating conditions fall outside the tested capability
envelope?

*Related: [mechanism](../taxonomy/mechanism.md) — capability mismatch,
environmental mismatch.*

## 2. Users

Which abilities, access needs, expectations, or prior experiences are
implicitly assumed?

*Related: [locus](../taxonomy/locus.md) — human factors;
[mechanism](../taxonomy/mechanism.md) — accessibility, expectation
mismatch.*

## 3. Recovery

How will the system detect, explain, escalate, and recover from
failures?

*Related: [mechanism](../taxonomy/mechanism.md) — insufficient
recovery, insufficient transparency.*

## 4. Workflow

What new monitoring, intervention, hand-offs, or hidden work does the
robot create for staff?

*Related: [locus](../taxonomy/locus.md) — organisation / workflow;
[mechanism](../taxonomy/mechanism.md) — workflow mismatch.*

## 5. Context

Which physical, social, cultural, or organisational conditions could
invalidate laboratory assumptions?

*Related: [locus](../taxonomy/locus.md) — physical environment;
[mechanism](../taxonomy/mechanism.md) — environmental mismatch.*

## 6. Maintenance

What changes after weeks or months of operation, including wear,
software updates, connectivity changes, recurring faults, and staff
turnover?

*Related: [stage](../taxonomy/stage.md) — sustained operation;
[mechanism](../taxonomy/mechanism.md) — maintenance burden.*

## 7. Economics

Which manufacturing, integration, supervision, maintenance, and
scaling costs are absent from the prototype demonstration?

*Related: [locus](../taxonomy/locus.md) — economic / business;
[mechanism](../taxonomy/mechanism.md) — cost / ROI mismatch.*

## 8. Accountability

Who owns intervention and decision-making when human, robot,
service-provider, and organisational factors interact?

*Related: [locus](../taxonomy/locus.md) — governance / safety;
[mechanism](../taxonomy/mechanism.md) — stakeholder misalignment.*

## Three practice implications

1. **Design for recovery, not only failure prevention.** Long-running
   systems require explicit escalation pathways, intelligible failure
   communication, and mechanisms for returning to normal operation.
2. **Evaluate deployment viability, not only task accuracy.** User
   adoption, accessibility, workflow fit, maintenance burden, and
   scaling cost are part of real-world system performance.
3. **Engineer exception-handling roles.** Automation can redistribute
   work rather than remove it; responsibility for monitoring,
   intervention, hand-offs, and recovery should be defined before
   deployment.
