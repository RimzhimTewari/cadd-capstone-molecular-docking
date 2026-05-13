# Protein Information #
## Protein Overview ## 
**Protein Name:** SARS-CoV-2 Main Protease (Mpro)           
**PDB ID:** 7SFB

---
## Biological Relevance
The SARS-CoV-2 main protease (Mpro), also called 3CLpro, is a viral enzyme that helps the virus replicate. It does this by cutting long viral polyproteins into smaller, working proteins that the virus needs to finish its life cycle. Because this enzyme is so important for coronavirus replication, and because there aren’t close human equivalents, it’s often treated as a good target for antiviral drug development.


Our work on SARS-CoV-2 Mpro offers a structural starting point for later bioinformatics tasks, like molecular docking and virtual screening, to look for possible inhibitors and find promising ligands.

## Structural Information
| Parameter |	Details |
|---|---|
|Experimental Method|	X-RAY DIFFRACTION |
|Resolution|	1.90 Å |
| Organism	| Severe acute respiratory syndrome coronavirus 2|
| Presence of Co-crystallized Ligand	|Yes, ML101|

---
## Protein Preparation
We downloaded the original protein structure from the Protein Data Bank (PDB) and got it ready for computational analysis.


Protein preparation steps included:

- Removal of unnecessary molecules such as water
- Structural cleaning
- Addition of hydrogens where required
- Preparation for molecular docking analysis

Prepared protein files were stored in:

```text
data/protein/prepared/
```

---
## PyMOL Visualization

PyMOL was used for visualization and structural inspection of the protein structure.


## Justification for Protein Selection
We used the protein structure with PDB ID 7SFB in a computational drug discovery training workflow that focuses on molecular docking and analyzing protein–ligand interactions. This structure worked well for the task because it has high-resolution crystal data and includes a co-crystallized ligand, which helps when doing docking-based computational studies.


Since SARS-CoV-2 Mpro is strongly tied to viral replication, it also remains a common and well-studied target in antiviral computational research.docking and protein–ligand interaction analysis. The structure was considered suitable for this study due to its high-resolution crystal data and the presence of a co-crystallized ligand, which supports docking-based computational analysis.

The biological relevance of SARS-CoV-2 main protease (Mpro) in viral replication further makes it a widely studied target in antiviral computational research.
