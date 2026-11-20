# H1 supplier lanes, geometric orbit ladder and non-reopening bridge routing
Atlas version: R2C15_V15_R1
Record ID: ZT-UK-H1-INDEPENDENT-ACCESS-AND-GEOMETRIC-ORBIT-LADDER-001
Source status: Inherited reading view
Historical: false
Full atlas: https://zenodo.org/records/24383891

## Target claim or question

How is H1 supplied without target leakage, how are higher orbit ratios derived, and which residual bridges genuinely remain?

## Minimal dependency spine

- ZT-RG-LOCAL-UNITS-001
- ZT-RG-H1-ZERO-LEDGER-SQUARE-RATE-MAP-001
- ZT-RG-H1-INDEPENDENT-ACCESS-THREE-LANE-REGISTRY-001
- ZT-RG-BOUND-ELECTRON-L1-ORBIT-CLOSURE-001
- ZT-RG-GEOMETRIC-HYDROGEN-ORBIT-N-SQUARED-LADDER-001
- ZT-RG-H1-DEPENDENCY-SUPPLIER-EDGE-CONTRACT-001

## Included current nodes

- ZT-RG-H1-INDEPENDENT-ACCESS-THREE-LANE-REGISTRY-001
- ZT-RG-GEOMETRIC-HYDROGEN-ORBIT-N-SQUARED-LADDER-001
- ZT-RG-H1-IONIZATION-ENERGY-TWO-NONCIRCULAR-INVERSE-RECOVERIES-001
- ZT-RG-H1-DEPENDENCY-SUPPLIER-EDGE-CONTRACT-001

## Active bridges

- ZT-BRIDGE-HYDROGEN-INTEGER-N-SELECTION-DYNAMICS-001
- ZT-BRIDGE-ZT-ALPHA-ORIGIN-001
- ZT-BRIDGE-H1-FRAME-SCALE-TO-ELECTRON-ORBIT-GEOMETRY-001

## Resolved bridges

- ZT-BRIDGE-HYDROGEN-N1-ZERO-LEDGER-RATE-RECOVERY-001
- ZT-BRIDGE-GEOMETRIC-HYDROGEN-ORBIT-N-SQUARED-LADDER-RECOVERY-001

## Assumptions

- q-square user rule
- N_n=n
- lambda_n=n lambda_1
- virial/de Broglie closure only in the energy lane

## Intuition route

Find H1 once on the project ledger, build relative orbit geometry from closure counts, and keep empirical energy reconstruction in a separate lane.

## Geometry route

N_n=n and lambda_n=n lambda_1 imply C_Hn=n^2 C_H1.

## Mathematical route

q_e,L1=4*pi/D -> q_H1=16*pi^2/D^2; separately C_H1=h/sqrt(2 mu_H E_ion).

## Logical route

A supplied prerequisite cannot be reopened by a deeper residual. Mixed bridges are split by claim ceiling.

## Observational route

No empirical target in the internal H1 or relative ladder lanes; E_ion is explicit in the physical inverse reconstruction lane.

## Evidence independence assessment

The three lanes have different decisive inputs and must not be counted as independent confirmations of one claim.

## Important negative results

- C22 asymptotic cycle is dependent
- energy routes share E_ion
- relative n-squared geometry does not derive absolute SI H1

## Open stoplines

- ZT-BRIDGE-HYDROGEN-INTEGER-N-SELECTION-DYNAMICS-001
- ZT-BRIDGE-ZT-ALPHA-ORIGIN-001
- ZT-BRIDGE-H1-FRAME-SCALE-TO-ELECTRON-ORBIT-GEOMETRY-001

## Falsification conditions

- A recovered source contradicts N_n=n or lambda_n=n lambda_1
- The input audit finds target-equivalent leakage
- A claimed consumer requires a quantity outside the supplier ceiling

## Downstream impact

H1, alpha, hydrogen clock, L3 arrival, gravity response and general-n routing.

## Code data evidence

- build_zero_theory_v054.py
- ZERO_THEORY_CORE_NO_REGRESSION_AUDIT_v0_54.md

## Candidate paper node set

- ZT-RG-H1-INDEPENDENT-ACCESS-THREE-LANE-REGISTRY-001
- ZT-RG-GEOMETRIC-HYDROGEN-ORBIT-N-SQUARED-LADDER-001
- ZT-RG-H1-IONIZATION-ENERGY-TWO-NONCIRCULAR-INVERSE-RECOVERIES-001

## Achievement ids

- ZT-ACH-H1-NO-TARGET-SUPPLIER-AND-ROUTING-REPAIR-001
- ZT-ACH-GEOMETRIC-HYDROGEN-N-SQUARED-LADDER-001

## Achievement review state

ACHIEVEMENT-LINKED

## Provenance

- C7-C8 and v0.54 canonical integration
