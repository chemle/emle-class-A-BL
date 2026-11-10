# EMLE Enzymes Paper

Supporting data for [**"Chemical Accuracy for Carbapenem Breakdown by Class A beta-Lactamases Using a Transferable Embedded Machine-Learned Potential"
**](https://chemrxiv.org/doi/abs/10.26434/chemrxiv.15008538/v1).

---

## Directory Structure


### `models/`
ML models trained. Includes:

- `BL_emle_model.mat`: EMLE model for the Class-A beta lactamase with meropenem systems
- `BL_MACE.model`: MACE model for the Class-A beta lactamase with meropenem systems

Each enzyme directory contains simulation files for each system. Includes:

- `parm7`: AMBER topology file  
- `rst`: relaxed structure  
- `in`: example `sander` input file for Umbrella Sampling  
- `restr`: example restraint file with Umbrella Sampling bias

---
