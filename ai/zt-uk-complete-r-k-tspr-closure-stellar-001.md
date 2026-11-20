# Complete R_H–K_ch–TSPR closure and stellar comparison
Atlas version: R2C15_V15_R1
Record ID: ZT-UK-COMPLETE-R-K-TSPR-CLOSURE-STELLAR-001
Source status: Inherited reading view
Historical: false
Full atlas: https://zenodo.org/records/24383891

## Target claim or question

Can all three declared chronometric components be retained in one target-blind closure, compared with standard and null controls, without inventing a spectral law?

## Minimal dependency spine

- ZT-RG-STANDARD-SR-NESTED-CHRONOMETRIC-LABEL-001
- ZT-RG-HYDROGEN-LEGACY-SPATIAL-TEMPORAL-RESIDUAL-001
- ZT-RG-TSPR-BETA-PARAMETERIZATION-AUDIT-001
- ZT-RG-COMPLETE-R-K-TSPR-CLOSURE-COMPARATOR-001
- ZT-RG-COMPLETE-CLOSURE-STELLAR-COMPARISON-001

## Included current nodes

- ZT-RG-STANDARD-SR-NESTED-CHRONOMETRIC-LABEL-001
- ZT-RG-HYDROGEN-LEGACY-SPATIAL-TEMPORAL-RESIDUAL-001
- ZT-RG-TSPR-BETA-PARAMETERIZATION-AUDIT-001
- ZT-RG-MACRO-GEOMETRIC-ROTATION-FRAME-CADENCE-FIREWALL-001
- ZT-RG-S2-PROJECT-NATIVE-CHRONOMETRIC-COMPARATOR-001
- ZT-RG-COMPLETE-R-K-TSPR-CLOSURE-COMPARATOR-001
- ZT-RG-COMPLETE-CLOSURE-STELLAR-COMPARISON-001
- ZT-RG-HYDROGEN-CLOCK-OPERATIONAL-TIME-READOUT-001

## Active bridges

- ZT-BRIDGE-HYDROGEN-LEGACY-EPSILON-TO-CHRONOMETRIC-BETA-001
- ZT-BRIDGE-TSPR-CLOCK-LENGTH-PROJECTION-001
- ZT-BRIDGE-CHRONOMETRIC-K-TO-HYDROGEN-SPECTRAL-OBSERVABLE-001
- ZT-BRIDGE-COMPLETE-R-K-TSPR-CLOSURE-TO-SPECTRAL-OBSERVABLE-001

## Assumptions

- epsilon=beta_kin
- k_dir/R0=beta_kin
- Q_comp is the equality closure of K_ch and R_H/Pi
- cQ_comp is used only as a velocity-equivalent comparator on the stored baseline

## Intuition route

R_H, K_ch and TSPR are three coordinated descriptions of one conditional state. Coherence is checked by agreement, not by adding them.

## Geometry route

TSPR right triangle gives Pi=R_rec/R0; conditional k_dir/R0=beta_kin gives Pi=alpha.

## Mathematical route

R_H=beta^2; K_ch=gamma beta^2; Pi=alpha; therefore K_ch=R_H/Pi=1/Pi-Pi.

## Logical route

Fail closed unless both bridges and equality pass; preserve ablations as controls; never select by target closeness.

## Observational route

Frozen baseline -> standard comparator / null control / cQ_comp comparator -> stored observation and sigma. Emission and detector mapping remain open.

## Evidence independence assessment

The equality views share beta and bridge assumptions; S2 rows overlap and S38 dependent rows are not independent. Numerical improvement is descriptive only.

## Important negative results

- S38 null control is better than standard and complete closure
- 2022 holdout remains an 8.71-sigma miss
- no line-specific hydrogen prediction
- no algebraic sum or component selector

## Open stoplines

- ZT-BRIDGE-COMPLETE-R-K-TSPR-CLOSURE-TO-SPECTRAL-OBSERVABLE-001

## Falsification conditions

- Conditional component views fail the frozen equality tolerance.
- A preregistered line-specific likelihood rejects the closure or reverses its sign.
- Independent multi-object holdouts perform no better than standard/null controls.

## Downstream impact

- hydrogen spectral prediction
- stellar chronometric comparison
- component coherence
- source-to-detector likelihood

## Code data evidence

- ZERO_THEORY_COMPLETE_R_K_TSPR_CLOSURE_CALCULATOR_v0_9.py
- ZERO_THEORY_COMPLETE_CLOSURE_STELLAR_TEST_RUNNER_v0_24.py
- ZERO_THEORY_STELLAR_REPAIR_TEST_CASES_v0_16.json

## Candidate paper node set

- ZT-RG-COMPLETE-R-K-TSPR-CLOSURE-COMPARATOR-001
- ZT-RG-COMPLETE-CLOSURE-STELLAR-COMPARISON-001

## Portfolio state

FREEZE-CHECKPOINT / SWITCH-TO-ENABLING-DEPENDENCY — derive and preregister the complete source-to-detector spectral bridge before more post-hoc rows.

## Achievement ids

- ZT-ACH-COMPLETE-CHRONOMETRIC-CLOSURE-AND-NEGATIVE-HOLDOUT-001

## Achievement review state

ACHIEVEMENT-LINKED

## Achievement summary

R_H, K_ch, and TSPR were retained as a complete named state and connected through an explicit equality gate rather than addition or post-hoc selection; the six-case comparison, dependence warnings, stronger null control, and 8.71-sigma S38 holdout failure were frozen together.

## Achievement portfolio

~~~json
[
  {
    "achievement_id": "ZT-ACH-COMPLETE-CHRONOMETRIC-CLOSURE-AND-NEGATIVE-HOLDOUT-001",
    "achievement_status": "CURRENT-PARTIAL",
    "summary": "R_H, K_ch, and TSPR were retained as a complete named state and connected through an explicit equality gate rather than addition or post-hoc selection; the six-case comparison, dependence warnings, stronger null control, and 8.71-sigma S38 holdout failure were frozen together.",
    "exact_remaining_limit": "No line identity, emission law, sign, propagation model, nuisance likelihood, or independent source-to-detector spectral prediction has been derived."
  }
]
~~~

## Why scientifically nontrivial

It creates a coherent falsifiable comparator, exposes shared information, and treats a damaging holdout failure as scientific knowledge rather than hiding it.

## Progress delta

The closure algebra, executable guardrails, comparisons, nulls, and failure are jointly reproducible.

## Exact remaining limit

No line identity, emission law, sign, propagation model, nuisance likelihood, or independent source-to-detector spectral prediction has been derived.

## Achievement balance

~~~json
{
  "value": "It creates a coherent falsifiable comparator, exposes shared information, and treats a damaging holdout failure as scientific knowledge rather than hiding it.",
  "claim_ceiling": "No line identity, emission law, sign, propagation model, nuisance likelihood, or independent source-to-detector spectral prediction has been derived.",
  "anti_promotion": "Preserve the stated epistemic and resolution labels; scientific value does not promote a definition, assumption, diagnostic, or conditional result to an independently derived empirical law."
}
~~~
