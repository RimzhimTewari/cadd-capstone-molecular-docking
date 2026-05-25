# Molecular Docking and ADMET Analysis of Selected Therapeutic Compounds Against SARS-CoV-2 Main Protease (7SFB)

## Overview

This repository contains a beginner-level Computer-Aided Drug Design (CADD) capstone project focused on the computational analysis of the SARS-CoV-2 Main Protease (Mpro) structure (PDB ID: 7SFB). The project was designed to explore fundamental drug discovery workflows using a combination of structure-based bioinformatics and molecular modeling approaches.

The study included protein preparation, binding site prediction, drug-likeness screening, ADMET prediction, AlphaFold3 structure comparison, molecular docking, and protein–ligand interaction analysis using a selected library of therapeutic compounds.
 
This project was completed as part of a structured virtual research training program and aims to demonstrate practical understanding of essential computational biology and CADD workflows in a reproducible and well-documented format.

---

## Objectives

- To prepare and analyze the SARS-CoV-2 Main Protease (7SFB) structure for structure-based computational studies.

- To evaluate the drug-likeness and ADMET properties of selected therapeutic compounds using in silico screening approaches.

- To identify and examine potential binding pockets within the target protein structure.

- To compare experimentally derived and AlphaFold3-predicted protein structures for structural assessment.

- To perform molecular docking studies in order to investigate possible protein–ligand interactions between 7SFB and the selected compounds.

- To visualize and interpret docking interactions using molecular visualization tools.

---

## Workflow

1. Retrieval of the 7SFB protein structure from the Protein Data Bank (PDB)

2. Protein cleaning and preparation for computational analysis

3. Ligand collection and structure preparation from public chemical databases

4. Drug-likeness screening of selected compounds

5. Binding site prediction using the prepared protein structure

6. ADMET property prediction and evaluation

7. AlphaFold3 structure prediction and comparison with the experimental structure

8. Molecular docking of selected ligands against the target protein using PyRx

9. Visualization and interpretation of protein–ligand interactions using Discovery Studio Visualizer


## Tools and Software Used

| Tool / Database | Purpose |
|------------------|---------|
| Protein Data Bank (PDB) | Retrieval of the SARS-CoV-2 Main Protease structure (7SFB) |
| PubChem | Collection of ligand structures and chemical information |
| PyRx | Molecular docking and ligand energy minimization |
| Discovery Studio Visualizer | Visualization and analysis of protein–ligand interactions |
| SwissADME | Drug-likeness screening and physicochemical property evaluation |
| pkCSM / ADMETlab | ADMET property prediction |
| DoGSiteScorer | Binding site prediction and pocket analysis |
| AlphaFold3 | Protein structure prediction and structural comparison |


## Repository Structure

```text
├── Protein_Preparation/
├── Druglikeness_Screening/
├── Binding_Site_Prediction/
├── ADMET_Analysis/
├── AlphaFold3_Comparison/
├── Molecular_Docking/
├── Interaction_Analysis/
├── Figures/
├── Tables/
├── README.md
```



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
