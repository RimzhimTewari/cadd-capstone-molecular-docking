# Molecular Docking Analysis

## Overview

Molecular docking was performed to study the possible interactions between the selected ligands and the 7SFB protein structure. Docking analysis was carried out using PyRx with AutoDock Vina as the docking engine.

The workflow included:

- protein preparation
- ligand preparation
- energy minimisation
- docking grid configuration
- molecular docking
- docking pose selection
- protein–ligand interaction analysis

Interaction visualisation and analysis were further performed using BIOVIA Discovery Studio Visualizer.

---

## Folder Structure

### `best_poses/`

Contains the selected best docking pose files for all ligands.

### `figures/`

Contains PyRx workflow screenshots including protein preparation, ligand preparation, docking execution and docking result visualisations.

### `raw_results/`

Contains complete raw molecular docking output files and docking results.

### `discovery_studio/`

Contains Discovery Studio interaction analysis figures and interaction interpretation files.

---

## Docking Summary

The docking summary table containing the selected best docking poses and binding affinity scores is available in:

`docking_summary.csv`

The complete docking output generated during molecular docking is available in:

`raw_results/full_docking_results.csv`

---

## Software Used

- PyRx
- AutoDock Vina
- BIOVIA Discovery Studio Visualizer

---

## Notes

The docking results presented in this project are based on computational prediction methods and should be interpreted as preliminary observations. Further experimental and advanced computational validation would be required to confirm biological activity and binding behaviour.
