# Computational Workflow

## Overview

This project follows a standard computational drug discovery workflow to evaluate selected ligands against the protein target 7SFB using molecular docking and pharmacokinetic prediction approaches.

---

## Workflow Steps

### 1. Protein Retrieval and Preparation

- Protein structure retrieved from the Protein Data Bank (PDB ID: 7SFB)
- Water molecules removed
- Protein cleaned and prepared for docking analysis
- Polar hydrogens added where required

---

### 2. Ligand Collection and Preparation

- Ligand structures collected in `.sdf` format
- Ligand files were organized for computational analysis
- Ligands prepared before docking

---

### 3. Drug-likeness Screening

- Drug-likeness properties evaluated using SwissADME
- Physicochemical parameters analyzed
- Lipinski-related properties reviewed

---

### 4. ADMET Prediction

- Pharmacokinetic and toxicity-related properties predicted using ADMETlab
- Absorption and distribution-related parameters evaluated
- Preliminary toxicity indicators reviewed

---

### 5. Molecular Docking

- Docking analysis performed using PyRx
- Binding affinity scores evaluated in kcal/mol
- Differences in predicted binding affinity were observed among the ligands

---

### 6. Interaction Analysis

- Protein–ligand complexes visualized
- Binding interactions and amino acid contacts analyzed
- Interaction patterns were compared across different ligands
  
---

## Workflow Summary

Protein Preparation → Ligand Preparation → Drug-likeness Screening → ADMET Prediction → Molecular Docking → Interaction Analysis
