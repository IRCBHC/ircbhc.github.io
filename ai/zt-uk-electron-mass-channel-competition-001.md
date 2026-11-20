# Material-observer reference and L1/L2 competing mass-readout channels
Atlas version: R2C15_V15_R1
Record ID: ZT-UK-ELECTRON-MASS-CHANNEL-COMPETITION-001
Source status: Inherited reading view
Historical: false
Full atlas: https://zenodo.org/records/24383891

## Target claim or question

How can the same electron structure produce an observer-owned relational mass readout when L1/L2 accessibility may compete with distance/coupling and the material observer reference may itself participate physically?

## Minimal dependency spine

- ZT-RG-RELATIONAL-MASS-READOUT-001
- ZT-RG-MASS-THREE-LEVEL-READOUT-001
- ZT-RG-MASS-OBSERVER-PHASE-READOUT-001
- ZT-RG-ELECTRON-L1L2-MASS-CHANNEL-001

## Included current nodes

- ZT-RG-ROOT-REFERENCE-OWNERSHIP-001
- ZT-RG-RELATIONAL-MASS-READOUT-001
- ZT-RG-MASS-THREE-LEVEL-READOUT-001
- ZT-RG-MASS-OBSERVER-PHASE-READOUT-001
- ZT-RG-ELECTRON-COMPTON-MASS-INTERFACE-001
- ZT-RG-ELECTRON-L2-SIX-CHANNEL-READOUT-001
- ZT-RG-ELECTRON-L1L2-MASS-CHANNEL-001
- ZT-RG-ELECTRON-INTERNAL-RATE-WAVE-COMPATIBILITY-AUDIT-001

## Active bridges

- ZT-BRIDGE-RELATIONAL-MASS-READOUT-01
- ZT-BRIDGE-RELATIONAL-MASS-READOUT-02
- ZT-BRIDGE-MASS-OBSERVER-ENTRAINMENT-LAW-001
- ZT-BRIDGE-ELECTRON-L1L2-MASS-WEIGHTS-001
- ZT-BRIDGE-ELECTRON-L1L2-CROSSOVER-LAW-001
- ZT-BRIDGE-INTERNAL-RATE-TO-OBSERVER-RESOLVABILITY-001

## Assumptions

- L2-more-local/L1-longer-range hierarchy is qualitative only
- observer reference variables are physical readout variables; entrainment law not derived
- candidate dominance index is USER-DEFINITION/FORMALIZATION-CANDIDATE

## Intuition route

Household-appliance red/blue field analogy: local dominance and long-range background can exchange dominance through a mixed region; the question is which phase structure supplies the material observer reference.

## Geometry route

Electron L1/L2 internal structure -> observer position measured relative to each layer radius -> channel accessibility/resolvability.

## Mathematical route

A_i=K_i C_i R_Li; crossover |A1|=|A2|; candidate D_i proportional to N_i^obs |DeltaOmega_i:O|/(r/R_i).

## Logical route

Channel existence != visibility; frame translation != range attenuation; same Sigma_e != same observer readout; common 1/r alone cannot generate crossover when other factors are distance-independent.

## Observational route

No experimental mass mapping yet. SI calibration and proton comparison remain downstream stoplines.

## Evidence independence assessment

No measured electron mass is used upstream; this checkpoint is semantic/formalization work, not an empirical success.

## Important negative results

- spoke separation alone does not derive attenuation
- a common explicit 1/r factor alone does not create crossover if the remaining factors are r-independent
- different readout does not imply changed electron ontology

## Open stoplines

- ZT-BRIDGE-MASS-OBSERVER-ENTRAINMENT-LAW-001
- ZT-BRIDGE-ELECTRON-L1L2-MASS-WEIGHTS-001
- ZT-BRIDGE-ELECTRON-L1L2-CROSSOVER-LAW-001
- ZT-BRIDGE-INTERNAL-RATE-TO-OBSERVER-RESOLVABILITY-001
- ZT-BRIDGE-RELATIONAL-MASS-READOUT-02

## Falsification conditions

- A first-principles derivation shows no observer-dependent channel accessibility or no L1/L2 range difference
- The same derived functional cannot be applied unchanged to proton/electron
- Any proposed kernel requires target-mass fitting

## Downstream impact

- electron observed-mass program
- proton/electron common mass functional
- SI calibration
- observer-resolvability program

## Code data evidence

- apply_zero_theory_mass_readout_channel_competition_update_v0_21.py

## Candidate paper node set

- ZT-RG-RELATIONAL-MASS-READOUT-001
- ZT-RG-MASS-THREE-LEVEL-READOUT-001
- ZT-RG-MASS-OBSERVER-PHASE-READOUT-001
- ZT-RG-ELECTRON-L2-SIX-CHANNEL-READOUT-001
- ZT-RG-ELECTRON-L1L2-MASS-CHANNEL-001

## Achievement ids

- ZT-ACH-ELECTRON-MASS-READOUT-ARCHITECTURE-001

## Achievement review state

ACHIEVEMENT-LINKED

## Achievement summary

Mass was decomposed into structural content, observer-accessible channel projection, material-observer relational response, and SI calibration, replacing the superseded shortcut that treated an L2 quantity as total mass.

## Achievement portfolio

~~~json
[
  {
    "achievement_id": "ZT-ACH-ELECTRON-MASS-READOUT-ARCHITECTURE-001",
    "achievement_status": "CURRENT-PARTIAL",
    "summary": "Mass was decomposed into structural content, observer-accessible channel projection, material-observer relational response, and SI calibration, replacing the superseded shortcut that treated an L2 quantity as total mass.",
    "exact_remaining_limit": "The quantitative channel kernel, observer entrainment law, common electron/proton functional, and calibration remain open."
  }
]
~~~

## Why scientifically nontrivial

This identifies the minimum physical interfaces any honest electron or proton mass derivation must cross and prevents a frame quantity from being renamed as measured mass.

## Progress delta

A common readout architecture and explicit L1/L2 competition boundary now exist.

## Exact remaining limit

The quantitative channel kernel, observer entrainment law, common electron/proton functional, and calibration remain open.

## Achievement balance

~~~json
{
  "value": "This identifies the minimum physical interfaces any honest electron or proton mass derivation must cross and prevents a frame quantity from being renamed as measured mass.",
  "claim_ceiling": "The quantitative channel kernel, observer entrainment law, common electron/proton functional, and calibration remain open.",
  "anti_promotion": "Preserve the stated epistemic and resolution labels; scientific value does not promote a definition, assumption, diagnostic, or conditional result to an independently derived empirical law."
}
~~~
