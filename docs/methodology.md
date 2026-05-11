# Methodology

## Protein Preparation

The protein structure corresponding to PDB ID: 7SFB was retrieved from the Protein Data Bank (PDB). Protein preparation involved cleaning the structure, removing unnecessary molecules such as water, and preparing the protein for docking analysis.

Prepared protein files were stored in the `data/protein/prepared/` directory.

---

## Ligand Dataset Preparation

Selected ligand structures were collected in `.sdf` format and organized under the ligand dataset directory. Ligands used in this study include structurally diverse small molecules from different pharmacological classes.

Ligand metadata and organization files were maintained for structured analysis.

---

## Drug-likeness Analysis

Drug-likeness properties were evaluated using SwissADME. Physicochemical parameters including molecular weight, lipophilicity, and Lipinski-related properties were reviewed to assess general drug-like characteristics.

Drug-likeness results were stored under the `results/druglikeness/` directory.

---

## ADMET Prediction

ADMET properties were evaluated using ADMETlab. Predicted parameters related to absorption, distribution, metabolism, excretion, and toxicity were analyzed for comparative assessment across ligands.

ADMET results and interpretation files were stored under the `results/admet/` directory.

---

## Molecular Docking

Molecular docking analysis will be performed using AutoDock Vina to evaluate predicted binding affinity between ligands and the target protein structure.

Docking scores and interaction outputs will be stored in the `results/docking/` directory.

---

## Interaction Visualization

Protein–ligand interaction visualization and structural interpretation will be performed using molecular visualization tools including PyMOL and Discovery Studio.
