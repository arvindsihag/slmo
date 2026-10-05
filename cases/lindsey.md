# Lindsey

**Domain:** Museum / public space
**Source:** Del Duchetto, Hanheide, and Kucukyilmaz (2023)

## Background

Lindsey, an autonomous tour-guide robot, operated in a public museum
for several years and travelled more than 1,300 km during its
deployment.

## Evidence

- Multi-year field operation.
- Recurring navigation and execution failures.
- Some failures required assistance from nearby non-expert humans.

## SLMO encoding

    <sustained operation,
     technical / environmental / human,
     insufficient autonomous recovery,
     human intervention (recoverable)>

## Operational lesson

Human assistance should not automatically be interpreted as evidence
that autonomy has failed. In persistent real-world operation,
appropriately designed human-in-the-loop recovery can itself be an
operational capability.

For practitioners: specify how the system detects that autonomous
recovery is insufficient, how it communicates the problem, whom it can
ask for assistance, and how normal operation resumes.

## Source

Del Duchetto, F., Hanheide, M., and Kucukyilmaz, A. *In-the-wild
failures in a long-term HRI deployment*. University of Lincoln, 2023.
