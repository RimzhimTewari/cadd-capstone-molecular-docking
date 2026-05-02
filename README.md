# Computational Drug Discovery: Molecular Docking and ADMET Analysis of 7SFB Protein and Selected Ligands
This project was completed as part of CADD in-silico laboratory training and further developed as a structured computational analysis of protein–ligand interactions using docking, ADMET prediction, and structural validation approaches.

## 🧬 Objective
To study the binding interactions and pharmacokinetic properties of selected small molecules against the protein target (PDB ID: 7SFB) using computational docking and ADMET prediction tools.

## 🧪 Protein Used
- PDB ID: 7SFB

## 💊 Ligands (to be analyzed)
1. Aspirin
2. Ibuprofen
3. Acetaminophen
4. Naproxen
5. Diclofenac
6. Caffeine
7. Theophylline
8. Metformin
9. Artemether
10. Lumefantrine


## ⚙️ Workflow
Protein Preparation → Ligand Preparation → Binding Site Prediction → Molecular Docking → Interaction Analysis → ADMET Prediction → Drug-likeness Evaluation

## 🧪 Methodology Details

- Protein preparation includes removal of water molecules and addition of polar hydrogens.
- Ligand structures will be retrieved and optimized before docking.
- Active binding site prediction will be performed using structural analysis tools.
- Molecular docking will be carried out using AutoDock Vina with grid-based scoring.
- Binding affinity will be evaluated based on docking scores (kcal/mol).
- Top ligand-protein complexes will be visualized for interaction analysis.

  ## 📊 Expected Outputs

- Binding affinity scores for each ligand
- Identification of key interacting amino acid residues
- Ranking of ligands based on docking scores
- ADMET profile classification (drug-like vs non-drug-like)
- 2D/3D interaction visualizations

## 🧰 Tools Used
- PyMOL
- AutoDock Vina
- Discovery Studio
- SwissADME
- ADMETlab
- AlphaFold (if applicable)

## 📁 Repository Structure
- data/ → raw input files (protein + ligands)
- results/ → docking, ADMET, and visualization outputs

## 📌 Status
Work in progress — ligands and docking analysis will be added soon.
