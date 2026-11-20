# Capacity response, receiver window and event-count separation
Atlas version: R2C15_V15_R1
Record ID: ZT-UK-SINGLE-ARRIVAL-RESPONSE-001
Source status: Reading view
Historical: false
Full atlas: https://zenodo.org/records/24383891

## Current semantic state

~~~json
true
~~~

## Target claim or question

How does one normalized arrival produce a capacity-weighted response without becoming multiple events?

## Minimal dependency spine

- ZT-RG-FOURLAYER-CAPACITY-EVENT-SEPARATION-001
- ZT-RG-SINGLE-ARRIVAL-LINEAR-CAPACITY-RESPONSE-001
- ZT-RG-RECEIVER-TICK-SIMULTANEOUS-PHASE-ARRIVAL-001

## Included current nodes

- ZT-RG-FOURLAYER-CAPACITY-EVENT-SEPARATION-001
- ZT-RG-SINGLE-ARRIVAL-LINEAR-CAPACITY-RESPONSE-001
- ZT-RG-RECEIVER-TICK-SIMULTANEOUS-PHASE-ARRIVAL-001

## Active bridges

- ZT-BRIDGE-SINGLE-ARRIVAL-RESPONSE-TO-PHYSICAL-BPHASE-001
- ZT-BRIDGE-ELECTRON-L1-PROTON-L3-COMMON-RECEIVER-WINDOW-001

## Assumptions

- linear single-arrival response

## Intuition route

One event can have differently weighted receiver response and multiple simultaneous normalized components.

## Geometry route

The receiver owns the common event window.

## Mathematical route

R_i^(1)=gamma w_Li; W_J=tau_J; Delta n_event,J=1.

## Logical route

Separate raw cycles, normalized arrivals, event count and response capacity.

## Observational route

No SI response map yet.

## Evidence independence assessment

The 4*pi-1 intensity is the capacity realization, not a second factor.

## Important negative results

- C3 source-owned duration inference superseded.
- 1826.488 not derived by Local one-Tick arrival.

## Open stoplines

- ZT-BRIDGE-SINGLE-ARRIVAL-RESPONSE-TO-PHYSICAL-BPHASE-001
- ZT-BRIDGE-ELECTRON-L1-PROTON-L3-COMMON-RECEIVER-WINDOW-001

## Falsification conditions

- Author supersedes the linear response rule.
- A derived response law requires nonlinear capacity.

## Downstream impact

Pairwise response and electron/proton readout.

## Code data evidence

- ZERO_THEORY_CORE_NO_REGRESSION_AUDIT_v0_57.md

## Candidate paper node set

- ZT-RG-SINGLE-ARRIVAL-LINEAR-CAPACITY-RESPONSE-001
- ZT-RG-RECEIVER-TICK-SIMULTANEOUS-PHASE-ARRIVAL-001

## Achievement ids

- ZT-ACH-SINGLE-ARRIVAL-RESPONSE-001

## Achievement review state

v0.57-REGISTERED

## Provenance

- Single-arrival appendix Revision C4.
