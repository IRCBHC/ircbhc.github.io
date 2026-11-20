# Proton reconstruction research trail and parked return point
Atlas version: R2C15_V15_R1
Record ID: ZT-UK-PROTON-RESEARCH-TRAIL-PARKED-001
Source status: Inherited reading view
Historical: false
Full atlas: https://zenodo.org/records/24383891

## Target claim or question

What was actually tested in the proton P1/P2 and follow-on reconstruction, what survives CURRENT correction, what failed/superseded, and exactly where should work resume without redoing or over-deepening the branch?

## Minimal dependency spine

- ZT-RG-ELECTRON-GLOBAL-ROTATION-LIFT-001
- ZT-RG-PROTON-INVERSION-TOPOLOGY-001
- ZT-RG-PROTON-POST-INVERSION-KINEMATICS-002
- ZT-RG-FOURLAYER-COMMON-MODE-INVARIANCE-001
- ZT-RG-PROTON-MIRROR-SUM-001
- ZT-RG-PROTON-PHASE-MODE-STRUCTURE-001
- ZT-RG-PROTON-INTERNAL-ANGULAR-MOMENTUM-001

## Included current nodes

- ZT-RG-PROTON-INVERSION-TOPOLOGY-001
- ZT-RG-PROTON-POST-INVERSION-KINEMATICS-002
- ZT-RG-FOURLAYER-COMMON-MODE-INVARIANCE-001
- ZT-RG-PROTON-MIRROR-SUM-001
- ZT-RG-PROTON-EIGHT-COMPONENT-READOUT-001
- ZT-RG-PROTON-PHASE-MODE-STRUCTURE-001
- ZT-RG-PROTON-SPIN-PAIR-LOCKING-001
- ZT-RG-PROTON-INTERNAL-ANGULAR-MOMENTUM-001
- ZT-RG-PROTON-FACE-LABELED-720-RETURN-001
- ZT-RG-PROTON-WOUND-PINNED-THREE-SECTOR-GEOMETRY-001

## Active bridges

- ZT-BRIDGE-PROTON-INVERSION-DYNAMICS-001
- ZT-BRIDGE-PROTON-OMEGA-PHYSICAL-TRANSLATION-001
- ZT-BRIDGE-8COMP-TO-3SECTOR-READOUT-001
- ZT-BRIDGE-LAYER-INERTIA-GEOMETRY-001
- ZT-BRIDGE-PROTON-THREE-SECTOR-PHYSICAL-IDENTITY-001
- ZT-BRIDGE-PROTON-SPIN-QUANTUM-MAP-001
- ZT-BRIDGE-PROTON-CHARGE-FRACTION-001
- ZT-BRIDGE-PROTON-MASS-READOUT-001

## Resolved bridges

- ZT-BRIDGE-MIRROR-SUM-DERIVATION-001
- ZT-BRIDGE-PROTON-RATE-SCAFFOLD-CONSISTENCY-001

## Assumptions

- inside-out proton inversion remains a model hypothesis
- common-mode operation is a model operation
- physical omega/inertia/readout maps remain open

## Intuition route

Preserve the branch as a marked laboratory bench: every useful test and failure remains indexed, and HISTORICAL v0.33 left that P1/P2 bench; v0.34 later resumed only the blind mass-readout branch.

## Geometry route

four-layer electron-derived scaffold -> radial inversion hypothesis -> common/relative decomposition -> mirror and field/readout tests

## Mathematical route

common additive mode cancels from pairwise differences; q=(2,1,-1,-2) gives scale-free mirror-sum and 1+2 relative-mode structure; absolute scale is not CURRENT.

## Logical route

Research history is preserved without granting superseded numerics CURRENT status. Surviving exact symbolic identities are separated from failed physical identifications.

## Observational route

No proton observable is claimed. Charge, mass, magnetic moment, quark identity and spin remain behind explicit bridges.

## Evidence independence assessment

Historical P1/P2 numerical products are mutually dependent on one toy scaffold; repeated internal identities are not independent empirical evidence.

## Important negative results

- old hybrid P1/P2 absolute zero crossings/gaps are superseded
- 90-degree E/B geometry alone did not reduce 8 labels to 3 persistent sectors
- pairwise beat magnitudes did not directly yield three sectors
- raw three-mode weights were not frame-invariant fixed quark weights
- relative spin phase alone did not guarantee nonzero net classical J
- face-labeled 720-degree return did not derive a quantum spinor

## Open stoplines

- ZT-BRIDGE-PROTON-OMEGA-PHYSICAL-TRANSLATION-001
- ZT-BRIDGE-LAYER-INERTIA-GEOMETRY-001
- ZT-BRIDGE-PROTON-THREE-SECTOR-PHYSICAL-IDENTITY-001
- ZT-BRIDGE-PROTON-SPIN-QUANTUM-MAP-001
- ZT-BRIDGE-PROTON-CHARGE-FRACTION-001
- ZT-BRIDGE-PROTON-MASS-READOUT-001

## Falsification conditions

- Any future continuation that requires restoring the purged absolute affine calibration is rejected unless the rate-ownership bridge is independently re-derived.
- Any physical proton claim must pass the relevant existing bridge without fitting the target observable.

## Downstream impact

- prevents duplicate proton simulation work
- preserves negative controls
- keeps common-mode theorem reusable outside proton
- protects electron frontier from proton depth drift
- v0.34 resumes only the blind mass-readout branch; historical negative controls remain active

## Code data evidence

- ZERO_THEORY_PROTON_P1P2_RESEARCH_TRAIL_v0_1.zip
- ZT-EVID-PROTON-P1P2-RESEARCH-TRAIL-001

## Portfolio state

HISTORICAL CHECKPOINT: v0.33 FREEZE-CHECKPOINT — PROTON PARKED. Superseded as CURRENT planning state by explicit USER-PRIORITY-OVERRIDE in v0.34; preservation semantics remain valid.

## Achievement ids

- ZT-ACH-PROTON-RESEARCH-TRAIL-RECOVERY-001
- ZT-ACH-FOURLAYER-COMMON-MODE-INVARIANCE-001
- ZT-ACH-PROTON-SECTOR-SPIN-RELATION-001
- ZT-ACH-PROTON-MINIMUM-CONSTITUENT-SPIN-GEOMETRY-001

## Achievement review state

ACHIEVEMENT-LINKED

## Achievement summary

Under the declared additive common-mode operation omega_i' = omega_i + Omega_C, every pairwise relative angular-rate difference is exactly invariant; the result survives the purge of obsolete absolute proton-rate calibrations.

## Achievement portfolio

~~~json
[
  {
    "achievement_id": "ZT-ACH-PROTON-RESEARCH-TRAIL-RECOVERY-001",
    "achievement_status": "HISTORICAL-VALUE-PRESERVED",
    "summary": "The P1/P2 simulation trail, snapshots, sweeps, gap relations, failures, and correction history were recovered and indexed while invalid absolute calibrations remained quarantined; the durable common-mode theorem is registered separately as a CURRENT achievement.",
    "exact_remaining_limit": "Archive recovery does not restore historical absolute calibrations or determine physical proton rate, inertia, or observer coupling."
  },
  {
    "achievement_id": "ZT-ACH-FOURLAYER-COMMON-MODE-INVARIANCE-001",
    "achievement_status": "CURRENT-CONDITIONAL",
    "summary": "Under the declared additive common-mode operation omega_i' = omega_i + Omega_C, every pairwise relative angular-rate difference is exactly invariant; the result survives the purge of obsolete absolute proton-rate calibrations.",
    "exact_remaining_limit": "The theorem is conditional algebra only; it does not derive dynamical synchronization, an absolute layer rate, proton inertia, spin, or observer readout."
  },
  {
    "achievement_id": "ZT-ACH-PROTON-SECTOR-SPIN-RELATION-001",
    "achievement_status": "CURRENT-CONDITIONAL",
    "summary": "For the declared wound-centered reflection parity, every C-even sector scalar has the exact form S=c(1,1,1)+d(-2,1,1), so two sectors are equal and the distinguished sector has the opposite-sign relative deviation with twice their magnitude; 500 Fourier audits reproduced the equality numerically.",
    "exact_remaining_limit": "The relation does not determine absolute angular momentum, proton spin 1/2, quark-spin assignments, or the physical parity/readout map."
  },
  {
    "achievement_id": "ZT-ACH-PROTON-MINIMUM-CONSTITUENT-SPIN-GEOMETRY-001",
    "achievement_status": "CURRENT-CONDITIONAL",
    "summary": "Six active phase cells were connected through antipodal pairing to three sectors; wound-centered Z2 yields a 1+2 sector geometry, and the exact C-even relation supplies the minimum conditional constituent/spin scaffold that opened blind mass bookkeeping.",
    "exact_remaining_limit": "This is not a derivation of QCD quarks, charge fractions, absolute constituent spins, proton spin 1/2, magnetic moment, or physical proton mass."
  }
]
~~~

## Why scientifically nontrivial

It extracts a reusable scale-free theorem from the historical P1/P2 work and cleanly separates durable relative structure from invalidated absolute calibration.

## Progress delta

The exact algebra is now a CURRENT standalone theorem with its own achievement route and an explicit conditional ceiling.

## Exact remaining limit

The theorem is conditional algebra only; it does not derive dynamical synchronization, an absolute layer rate, proton inertia, spin, or observer readout.

## Achievement balance

~~~json
{
  "value": "It extracts a reusable scale-free theorem from the historical P1/P2 work and cleanly separates durable relative structure from invalidated absolute calibration.",
  "claim_ceiling": "The theorem is conditional algebra only; it does not derive dynamical synchronization, an absolute layer rate, proton inertia, spin, or observer readout.",
  "anti_promotion": "Preserve the stated epistemic and resolution labels; scientific value does not promote a definition, assumption, diagnostic, or conditional result to an independently derived empirical law."
}
~~~
