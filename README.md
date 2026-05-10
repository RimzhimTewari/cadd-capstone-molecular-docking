# Computational Drug Discovery: Molecular Docking and ADMET Analysis of 7SFB Protein and Selected Ligands

## Overview

This project explores protein–ligand interactions using molecular docking and computational pharmacokinetic analysis against the target protein 7SFB. The workflow includes protein preparation, ligand screening, ADMET prediction, and docking-based interaction analysis using commonly used CADD tools.

---

## Objective

- Evaluate selected ligands against protein target 7SFB
- Perform drug-likeness and ADMET screening
- Analyze predicted binding interactions computationally
- Compare ligands based on pharmacokinetic and docking-related properties

---

## Protein Target

**PDB ID:** 7SFB

---

## Ligand Dataset

The ligand set used in this project was adapted from a workshop-based computational drug discovery exercise and includes structurally diverse small molecules with varying physicochemical and pharmacological properties.

### Ligands Included

- Aspirin
- Ibuprofen
- Acetaminophen
- Naproxen
- Diclofenac
- Caffeine
- Theophylline
- Metformin
- Artemether
- Lumefantrine

---

## Computational Workflow

Protein Preparation → Ligand Preparation → Drug-likeness Screening → ADMET Prediction → Molecular Docking → Interaction Analysis

---

## Tools Used

| Category | Tools |
|---|---|
| Molecular Visualization | PyMOL, Discovery Studio |
| Docking | AutoDock Vina |
| Drug-likeness Prediction | SwissADME |
| ADMET Prediction | ADMETlab |

---

## Repository Structure

```text
data/       -> input protein and ligand files
results/    -> ADMET, drug-likeness, and docking outputs
docs/       -> project documentation
```

---

## Current Status

- [x] Protein preparation completed
- [x] Ligand dataset collected
- [x] Drug-likeness analysis completed
- [x] ADMET analysis completed
- [ ] Molecular docking in progress
- [ ] Interaction visualization pending

---

## Disclaimer

This project is intended for educational and computational research purposes only. Docking and ADMET predictions are preliminary in silico analyses and do not represent experimental validation.
