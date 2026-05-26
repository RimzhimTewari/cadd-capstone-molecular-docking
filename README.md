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

---

## Tools and Software Used

| Tool / Database | Purpose |
|------------------|---------|
| Protein Data Bank (PDB) | Retrieval of the SARS-CoV-2 Main Protease structure (7SFB) |
| PubChem | Collection of ligand structures and chemical information |
| PyRx | Molecular docking and ligand energy minimization |
| Discovery Studio Visualizer | Visualization and analysis of protein–ligand interactions |
| SwissADME | Drug-likeness screening and physicochemical property evaluation |
| ADMETlab | ADMET property prediction |
| DoGSiteScorer | Binding site prediction and pocket analysis |
| AlphaFold3 | Protein structure prediction and structural comparison |

---

## Repository Structure

```text
├── data/
│   ├── ligands/
│   └── protein/
│
├── docs/
│
├── results/
│   ├── admet/
│   ├── binding_site/
│   ├── docking/
│   ├── druglikeness/
│   └── structure_prediction/
│
├── figures/
│
├── README.md
└── .gitignore
```

---

## Methodology

### Protein Preparation

The crystal structure of the SARS-CoV-2 Main Protease (PDB ID: 7SFB) was retrieved from the Protein Data Bank (PDB). The downloaded structure was examined and prepared for downstream computational analysis by removing unnecessary molecules and ensuring compatibility with molecular docking workflows.

The prepared protein structure was saved in PDB format and used for binding site prediction, molecular docking, and structural comparison studies performed in later stages of the project.

### Ligand Preparation

The selected therapeutic compounds were collected from the PubChem database in SDF format. The ligand set included common bioactive molecules provided as part of the capstone project.

Ligand structures were imported into PyRx for energy minimization and preparation prior to molecular docking. The prepared ligands were used for molecular docking analysis against the target protein structure, while the raw ligand information was used for drug-likeness screening and ADMET evaluation.

### Drug-Likeness Screening

Drug-likeness screening was performed to evaluate the physicochemical properties of the selected therapeutic compounds using SwissADME. Parameters related to molecular weight, lipophilicity, hydrogen bond donors and acceptors, and Lipinski’s Rule of Five were examined to assess the suitability of the compounds for potential oral bioavailability.

The screening results were used as a preliminary in silico assessment before molecular docking and ADMET analysis.

### Binding Site Prediction

Binding site prediction was performed using DoGSiteScorer to identify potential ligand-binding pockets within the SARS-CoV-2 Main Protease structure. The raw protein structure was used for this analysis in order to examine the native structural features of the protein before docking studies.

The identified binding pockets and associated residues were analyzed to support the selection of docking regions for subsequent molecular docking experiments.

### ADMET Prediction

ADMET prediction was carried out to evaluate the absorption, distribution, metabolism, excretion, and toxicity-related properties of the selected therapeutic compounds using ADMETlab.

The analysis provided a preliminary assessment of pharmacokinetic behavior and potential toxicity profiles before molecular docking interpretation. The raw ligand structures were used for ADMET evaluation.






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
