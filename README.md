# Simulation of Single Patch Colloids

This repository hosts the MSc thesis of **Najiya K K** titled  
*“Simulation of Single Patch Colloids”* (Central University of Punjab, 2024).

## 📄 Thesis
- [Download PDF](thesis.pdf)

## 🧪 Project Summary
Patchy colloids are colloidal particles with engineered surface patches that enable
directional bonding and programmable self-assembly. In this project, I performed
**molecular dynamics simulations** to study how **patch ratio** and **packing fraction**
influence the self-assembly behavior of single-patch colloids.

### Key aspects
- Interactions modeled using **Weeks–Chandler–Andersen (WCA)** and **Morse potentials**
- Periodic boundary conditions applied in 3D simulation box
- Structural analysis carried out using **OVITO**
- Cluster distributions processed and visualized

### Main results
- **Patch ratio < 1.0** → micelle-like clusters dominate  
- **Patch ratio > 1.0** → dimers, trimers, and linear structures dominate  
- **Packing fraction** has limited effect except at higher densities  
- Large clusters are rare but appear across different parameter regions

---

## 📊 Repository Contents
- `main.pdf` — Full MSc thesis document  
- `results/figures/` — Snapshots and histograms of cluster distributions  
- `results/cluster_data/` — Placeholder for exported CSV files of cluster size distributions  
- `analysis/` — Python scripts for independent re-analysis (to be added)

---

## 🔬 Independent Extension
As an extension to the MSc work, I am developing **Python-based post-processing tools**
for analyzing the exported cluster data. Planned features include:

- Average cluster size vs patch ratio and packing fraction  
- Cluster size distribution fits (exponential / power-law)  
- Phase-map visualization of self-assembly regimes  

All code will be available in `analysis/cluster_analysis.py`.

---

## 📖 Citation
If you refer to this work, please cite:

```bibtex
@mastersthesis{najiya2024patchycolloids,
  author = {Najiya K K},
  title = {Simulation of Single Patch Colloids},
  school = {Central University of Punjab},
  year = {2024}
}
