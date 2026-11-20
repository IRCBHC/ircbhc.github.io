# Local projection owner correction and Bohr diagnostic atlas
Atlas version: R2C15_V15_R1
Record ID: ZT-UK-LOCAL-PROJECTION-OWNER-BOHR-ATLAS-001
Source status: Inherited reading view
Historical: false
Full atlas: https://zenodo.org/records/24383891

## Target claim or question

Which owner holds 17.099 km, what are the valid one-step projections, and what does n_eq mean?

## Minimal dependency spine

- ZT-RG-LOCAL-EQUIVALENT-CIRCUMFERENCE-BOHR-ANCHORED-001
- ZT-RG-LOCAL-ELECTRON-PROTON-PROJECTION-STEP-REGISTRY-001
- ZT-RG-PROJECTION-CIRCUMFERENCE-BOHR-EQUIVALENT-N-ATLAS-001
- ZT-RG-BOHR-N0-PROTON-CIRCUMFERENCE-NO-GO-001

## Included current nodes

- ZT-RG-LOCAL-UNITS-001
- ZT-RG-ZERO-UNITS-001
- ZT-RG-LOCAL-ELECTRON-PROTON-PROJECTION-STEP-REGISTRY-001
- ZT-RG-PROJECTION-CIRCUMFERENCE-BOHR-EQUIVALENT-N-ATLAS-001
- ZT-RG-BOHR-N0-PROTON-CIRCUMFERENCE-NO-GO-001

## Active bridges

- ZT-BRIDGE-PROJECTION-RING-TO-PHYSICAL-ORBIT-OR-FRAME-SIZE-001

## Open stoplines

- ZT-BRIDGE-PROJECTION-RING-TO-PHYSICAL-ORBIT-OR-FRAME-SIZE-001

## Superseded bridges

- ZT-BRIDGE-HIST-C23-LOCAL-PROTON-OWNERSHIP-TO-IONIZATION-CIRCUMFERENCE-001
- ZT-BRIDGE-HIST-C23-DIMENSIONLESS-PROTON-READOUT-TO-METRIC-RADIUS-001

## Resolution state

PARTIALLY-RESOLVED

## Understanding routes

~~~json
{
  "owner": "Local is pivot",
  "proton": "one 4pi step below",
  "electron": "one 4pi step above",
  "diagnostic": "n_eq only"
}
~~~

## Important negative results

- C23 second division invalid
- n=0 not physical
- projection not material size

## Exact remaining limit

Derive the physical projection-to-size/orbit map and physical proton circumference.

## Portfolio state

OWNER CORRECTED / ARITHMETIC RESOLVED / PHYSICAL TRANSLATION OPEN

## Achievement ids

- ZT-ACH-LOCAL-PROJECTION-OWNER-STEP-CORRECTION-001

## Achievement review state

v0.53-REVIEWED

## Achievement summary

Preserves the author correction and removes the spurious magic-17 branch.
