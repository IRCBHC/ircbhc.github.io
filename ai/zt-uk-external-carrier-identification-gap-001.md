# External carrier, invariant-signal construction, clock/readout and observational firewalls
Atlas version: R2C15_V15_R1
Record ID: ZT-UK-EXTERNAL-CARRIER-IDENTIFICATION-GAP-001
Source status: Inherited reading view
Historical: false
Full atlas: https://zenodo.org/records/24383891

## Target claim or question

What is actually established by the train–rope carrier audit, and what still blocks a physical EM carrier test?

## Minimal dependency spine

- ZT-RG-ROOT-REFERENCE-OWNERSHIP-001
- ZT-RG-TRAIN-ROPE-TWO-BRANCH-IDENTIFICATION-001
- ZT-RG-LORENTZ-CONTRACTION-ONTOLOGY-FIREWALL-001
- ZT-RG-MATERIAL-DIMENSION-OUTPUT-GUARDRAIL-001
- ZT-RG-CLEANROOM-CARRIER-PHASE-BOND-001
- ZT-RG-PHASE-COUNT-CLOCK-FIREWALL-001
- ZT-RG-CARRIER-MATERIAL-CLOCK-IDENTIFICATION-FIREWALL-001

## Included current nodes

- ZT-RG-TRAIN-ROPE-TWO-BRANCH-IDENTIFICATION-001
- ZT-RG-PHASE-COUNT-CLOCK-FIREWALL-001
- ZT-RG-CARRIER-MATERIAL-CLOCK-IDENTIFICATION-FIREWALL-001
- ZT-RG-EXTERNAL-LOCAL-EM-ATMOSPHERIC-FIREWALL-001
- ZT-RG-GRACEFO-CARRIER-NEGATIVE-CONTROL-001
- ZT-RG-GPS-EQUATOR-ROTATIONAL-CLOCK-AUDIT-001
- ZT-RG-LORENTZ-CONTRACTION-ONTOLOGY-FIREWALL-001
- ZT-RG-TWO-WAY-PHASE-CLOCK-SELECTION-AUDIT-001
- ZT-RG-MATERIAL-CLOCK-CANONICAL-TWO-QUADRATURE-001
- ZT-RG-MATERIAL-DIMENSION-OUTPUT-GUARDRAIL-001
- ZT-RG-CLEANROOM-CARRIER-PHASE-BOND-001

## Active bridges

- ZT-BRIDGE-EM-EXTERNAL-CARRIER-PHYSICALITY-001
- ZT-BRIDGE-EXTERNAL-LOCAL-EM-CARRIER-RESIDUAL-LAW-001
- ZT-BRIDGE-CARRIER-MATERIAL-PHASE-RATE-001
- ZT-BRIDGE-CARRIER-MATERIAL-RELAXATION-001

## Assumptions

- toy external carrier branch
- constructed invariant-signal branch
- explicit atmosphere/instrument nuisance separation

## Intuition route

A rope can be externally owned while observers build a successful invariant-signal coordinate ledger; the ledger success does not identify who owns the physical carrier.

## Geometry route

local tangent train/rope -> common event set -> external/local propagation history -> intersatellite path control

## Mathematical route

u±v encounter rates; Lorentz-isomorphic coordinate construction; same-event phase-count invariance; moving-endpoint negative controls.

## Logical route

Mathematical adequacy != unique ontology; external carrier != unchanged clock; frequency != phase count; ordinary Doppler/light-time != carrier residual.

## Observational route

Atmospheric ground comparison is nuisance-dominated; GRACE-FO removes neutral atmosphere but not clock/laser law degeneracy; GPS 103.7 ns is a standard comparator with non-independent historical Zero-Theory provenance.

## Evidence independence assessment

No positive carrier evidence is registered. The current observational stages are negative controls / identifiability firewalls.

## Important negative results

- phase-product is not clock-free
- one-way GRACE-FO asymmetry is non-discriminating
- historical 103-ns match is not independent evidence
- two-way phase symmetry does not select a unique material-clock law
- C2 square-root mechanism is conditional on an underived internal conjugate-sector mapping
- Train-rope coordinate closure does not derive material deformation.
- Fixed transverse/radial invariance is not CURRENT physics.
- Static local null can remain non-discriminating in the clean-room toy if material geometry co-adjusts.

## Open stoplines

- ZT-BRIDGE-EM-EXTERNAL-CARRIER-PHYSICALITY-001
- ZT-BRIDGE-EXTERNAL-LOCAL-EM-CARRIER-RESIDUAL-LAW-001
- ZT-BRIDGE-CARRIER-MATERIAL-PHASE-RATE-001
- ZT-BRIDGE-CARRIER-MATERIAL-RELAXATION-001

## Falsification conditions

- A preregistered carrier law that predicts a residual and fails against appropriately controlled data rejects that specified carrier branch; null local tests do not refute a perfectly observationally hidden ontology.

## Downstream impact

- Lorentz audit paper
- external-vs-local EM tests
- material clock programme

## Code data evidence

- external_carrier_branch_v0_1.json
- invariant_signal_branch_v0_1.json
- audit_phase_product_discriminator_v0_1.py
- GRACEFO_EXTERNAL_CARRIER_SIGNATURE_REPORT_v0_1.md
- ZT_STAGE_C1_TWO_WAY_PHASE_CLOCK_AUDIT_REPORT_v0_1.md
- ZT_STAGE_C2_CANONICAL_TWO_QUADRATURE_CLOSURE_REPORT_v0_1.md

## Candidate paper node set

- ZT-RG-TRAIN-ROPE-TWO-BRANCH-IDENTIFICATION-001
- ZT-RG-PHASE-COUNT-CLOCK-FIREWALL-001
- ZT-RG-CARRIER-MATERIAL-CLOCK-IDENTIFICATION-FIREWALL-001

## Superseded bridges

- ZT-BRIDGE-CARRIER-MATERIAL-CLOCK-LAW-001

## Achievement ids

- ZT-ACH-EXTERNAL-CARRIER-IDENTIFICATION-FIREWALL-001

## Achievement review state

ACHIEVEMENT-LINKED

## Achievement summary

The project separated a possible external carrier, invariant signal construction, material-clock response, atmospheric effects, Doppler/light-time effects, and apparatus readout, and registered GRACE-FO/GPS-style controls against false carrier detection.

## Achievement portfolio

~~~json
[
  {
    "achievement_id": "ZT-ACH-EXTERNAL-CARRIER-IDENTIFICATION-FIREWALL-001",
    "achievement_status": "CURRENT",
    "summary": "The project separated a possible external carrier, invariant signal construction, material-clock response, atmospheric effects, Doppler/light-time effects, and apparatus readout, and registered GRACE-FO/GPS-style controls against false carrier detection.",
    "exact_remaining_limit": "No nondegenerate carrier state variable with a preregistered residual observable has been derived."
  }
]
~~~

## Why scientifically nontrivial

It demonstrates that several intuitive carrier signatures are observationally degenerate and specifies what a non-silent carrier theory would have to add.

## Progress delta

A falsifiable identification firewall and negative-control family now constrain future models.

## Exact remaining limit

No nondegenerate carrier state variable with a preregistered residual observable has been derived.

## Achievement balance

~~~json
{
  "value": "It demonstrates that several intuitive carrier signatures are observationally degenerate and specifies what a non-silent carrier theory would have to add.",
  "claim_ceiling": "No nondegenerate carrier state variable with a preregistered residual observable has been derived.",
  "anti_promotion": "Preserve the stated epistemic and resolution labels; scientific value does not promote a definition, assumption, diagnostic, or conditional result to an independently derived empirical law."
}
~~~
