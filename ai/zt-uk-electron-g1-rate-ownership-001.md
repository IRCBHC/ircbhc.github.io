# Electron geometry, frame-aware rates, G1 Maxwell and laboratory readout stoplines
Atlas version: R2C15_V15_R1
Record ID: ZT-UK-ELECTRON-G1-RATE-OWNERSHIP-001
Source status: Inherited reading view
Historical: false
Full atlas: https://zenodo.org/records/24383891

## Target claim or question

How does the current L1/L4 geometry connect to frame-owned rates, G1 Maxwell simulation, and ultimately laboratory response without mixing coordinate hooks, local clocks or normalized solver rates?

## Minimal dependency spine

- ZT-RG-ELECTRON-L1-LOCAL-OBSERVER-GEOMETRY-001
- ZT-RG-ELECTRON-L14-FROZEN-MAXWELL-PAIR-001
- ZT-RG-ELECTRON-FRAME-AWARE-RATE-REGISTRY-001
- ZT-SIM-G1-DYNAMIC-MAXWELL-V04-001
- ZT-RG-G-PENNING-OPERATIONAL-MAP-001

## Included current nodes

- ZT-RG-ROOT-REFERENCE-OWNERSHIP-001
- ZT-RG-LOCAL-UNITS-001
- ZT-RG-ELECTRON-L1-LOCAL-OBSERVER-GEOMETRY-001
- ZT-RG-ELECTRON-L1-EM-CROSS-SECTION-001
- ZT-RG-ELECTRON-L14-FROZEN-MAXWELL-PAIR-001
- ZT-RG-ELECTRON-NET-CHARGE-SOURCE-FAMILY-001
- ZT-RG-ELECTRON-FRAME-AWARE-RATE-REGISTRY-001
- ZT-TOOL-RATE-COMPILER-FRAME-AWARE-001
- ZT-SIM-G1-DYNAMIC-MAXWELL-V04-001
- ZT-RG-G-PENNING-OPERATIONAL-MAP-001
- ZT-RG-G1-SOLVER-CLOCK-RATE-ADAPTER-001
- ZT-RG-G1-PHASE-TO-SOURCE-TRANSPORT-CONTROL-001

## Active bridges

- ZT-BRIDGE-L1-MICRO-EM-COUPLING-001
- ZT-BRIDGE-ELECTRON-L1-RATE-SEMANTIC-DISAMBIGUATION-001
- ZT-BRIDGE-ELECTRON-G1-RATE-NORMALIZATION-001
- ZT-BRIDGE-G-INTERNAL-CHANNEL-MAP-001

## Assumptions

- 75/25 physical cross-section is user-defined/model-assumed
- G1 geometry is frozen for the current simulation branch
- Rate Compiler branch mappings are semantic/working definitions, not measured-frequency derivations

## Intuition route

Keep every clock and frame labeled before asking the field solver or laboratory readout to compare them.

## Geometry route

Corrected finite L1 geometry -> mirror+reverse L1/L4 pair -> source-family constraints -> G1 common simulation geometry.

## Mathematical route

Frame-owned rate registry -> exact solver clock omega_hat=omega*t_* -> recovered G1 source transport v_t=OMEGA*dX/dxi -> conditional phase-lock theorem OMEGA=omega_hat/k_xi. The simplest k_xi=6 L1 branch gives 1/3, not historical 0.72.

## Logical route

Timebase normalization is resolved. G1 OMEGA semantic ownership is recovered as source-sheet transport. The remaining P0 clause is the physical constitutive phase/source-current map; do not fit the historical OMEGA values.

## Observational route

Penning/anomaly comparison remains downstream of microscopic source/current and response-channel maps.

## Evidence independence assessment

Compiler/G1 diagnostics share project scaffolds and are not independent empirical evidence.

## Important negative results

- q=0.25 not EM-energy derived
- outward+sliding not isotropy
- nu1 hook not physical circulation by default
- G1 rate injection blocked
- direct phase-rate injection is not licensed
- six-cycle single-phase lock gives OMEGA_outer=1/3 != 0.72
- v0.4 weak-field replay reproducible; strong-field stress control remains FAIL

## Open stoplines

- ZT-BRIDGE-L1-MICRO-EM-COUPLING-001
- ZT-BRIDGE-ELECTRON-G1-RATE-NORMALIZATION-001
- ZT-BRIDGE-G-INTERNAL-CHANNEL-MAP-001

## Falsification conditions

- A derived source/current law inconsistent with required mirror/continuity controls
- No G1 mapping survives normalization and refinement
- Observed channel cannot be mapped without target fitting

## Downstream impact

Electron experimental simulation / g-factor channel mapping

## Code data evidence

- ZERO_THEORY_FRAME_AWARE_RATE_COMPILER_v0_2.zip
- ZERO_THEORY_TEAM_B_G1_DYNAMIC_MAXWELL_HANDOFF_v0_4.zip
- ZERO_THEORY_G1_RATE_COMPILER_INTEGRATION_v0_1_STAGE.zip
- ZERO_THEORY_G1_RATE_ADAPTER_CURRENT_v0_1.zip
- ZERO_THEORY_G1_ARCHIVE_RECOVERY_REPLAY_v0_1.zip
- ZERO_THEORY_PHASE_TO_G1_SOURCE_TRANSPORT_AUDIT_v0_1.zip

## Candidate paper node set

- ZT-RG-ELECTRON-L1-LOCAL-OBSERVER-GEOMETRY-001
- ZT-RG-ELECTRON-FRAME-AWARE-RATE-REGISTRY-001
- ZT-SIM-G1-DYNAMIC-MAXWELL-V04-001

## Achievement ids

- ZT-ACH-ELECTRON-G1-MAXWELL-RATE-CHECKPOINT-001

## Achievement review state

ACHIEVEMENT-LINKED

## Achievement summary

The electron L1/L4 geometry, frame-aware rate registry, exact solver-clock adapter, recovered G1 source-sheet transport meaning, reproducible weak-field simulation, and strong-field failure control were integrated into one owner-aware checkpoint.

## Achievement portfolio

~~~json
[
  {
    "achievement_id": "ZT-ACH-ELECTRON-G1-MAXWELL-RATE-CHECKPOINT-001",
    "achievement_status": "CURRENT-PARTIAL",
    "summary": "The electron L1/L4 geometry, frame-aware rate registry, exact solver-clock adapter, recovered G1 source-sheet transport meaning, reproducible weak-field simulation, and strong-field failure control were integrated into one owner-aware checkpoint.",
    "exact_remaining_limit": "No target-independent microscopic four-layer source/current law or anomaly/spin response eigenmode map has yet been derived."
  }
]
~~~

## Why scientifically nontrivial

It recovered what the historical solver parameter represented, prevented direct injection of a convenient phase rate, and converted simulation success and failure into auditable constraints on a future microscopic source law.

## Progress delta

Timebase conversion is exact, source-rate semantics are recovered, and the remaining constitutive and Penning-response gaps are sharply localized.

## Exact remaining limit

No target-independent microscopic four-layer source/current law or anomaly/spin response eigenmode map has yet been derived.

## Achievement balance

~~~json
{
  "value": "It recovered what the historical solver parameter represented, prevented direct injection of a convenient phase rate, and converted simulation success and failure into auditable constraints on a future microscopic source law.",
  "claim_ceiling": "No target-independent microscopic four-layer source/current law or anomaly/spin response eigenmode map has yet been derived.",
  "anti_promotion": "Preserve the stated epistemic and resolution labels; scientific value does not promote a definition, assumption, diagnostic, or conditional result to an independently derived empirical law."
}
~~~
