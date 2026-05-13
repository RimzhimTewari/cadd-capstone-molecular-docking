# Binding site prediction 

## Tools used 
I used DoGSiteScorer to identify potential binding pockets in the 7SFB protein structure.

---

## Selected Binding Pocket
The pocket P_0 was selected for further analysis because it overlapped with the region containing the co-crystallized ligand.

|Pocket ID | Volume (Å³) | Surface Area (Å²) | Drug Score | Simple Score |
|---|---|---|---|---|
| **P_0** |  642.94 | 776.96 | **0.75** | 0.44 |
| **P_1** | 446.02 | 686.04 | **0.78** | 0.3|
 
---
## Observations
I observed that the predicted binding pocket overlapped closely with the co-crystallised ligand region.

Most of the co-crystallized ligand appeared buried within the pocket, while a smaller region remained exposed to the protein surface.

The binding cavity appeared moderately deep and suitable for docking-based analysis.

---

## Interpretation
Although there is another predicted binding pocket that showed a slightly higher drug score of 0.78, I selected P_0 because its location corresponded with the experimentally observed ligand-binding region.

This overlap supported the selection of P_0 as the primary docking site for further molecular docking studies.

## Visualization

### Predicted Binding Pocket

![Binding Pocket](images/binding_site_overview.png)

### Pocket and Co-crystallized Ligand Overlap

![Pocket Overlap](images/pocket_overlap.png)
 


