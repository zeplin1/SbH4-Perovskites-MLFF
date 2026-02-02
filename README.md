# Comparative First-Principles and Machine-Learned Force Field Investigation of MAPbBrxI3-x and SbH4PbBrxI3-x Perovskites

This repository contains the supplementary datasets, machine-learned potentials, and input scripts supporting the research article submitted to **Computational Materials Science**.

**Author:** Veysel Çelik  
**Institution:** Siirt University, Department of Mathematics and Science Education

## Repository Contents

This repository is organized to provide transparency and reproducibility for the Molecular Dynamics (MD) simulations presented in the manuscript.

### 1. Machine-Learned Force Fields (MLFF)
The trained potential files used for the production runs are located in the respective folders:
* `MA/ML_FF`: Force field potential file for Methylammonium-based systems.
* `sbh4/ML_FF`: Force field potential file for Antimony Hydride-based systems.

These potentials were trained "on-the-fly" using VASP, based on the **optB86b-vdW** functional.

### 2. Training Datasets
* `ML_AB` files contain the *ab initio* reference configurations (energies, forces, and stress tensors) collected during the training trajectories.
* **MA-based Models:** ~1671 configurations.
* **SbH4-based Models:** ~2573 configurations.

### 3. Usage
These files can be used to:
1.  Reproduce the MD results (RMSD, RDF, thermal stability trends) discussed in the paper.
2.  Perform further simulations on these perovskite alloys using the pre-trained potentials.

---
*For any questions regarding the data, please contact: veysel3@gmail.com*
