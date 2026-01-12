# Deciphering Key Descriptors for Scaling Relationships in Graphene-Supported Pt<sub>n</sub> Clusters via Machine Learning

Subnanometer Pt clusters are promising electrocatalysts because they enable high noble-metal utilization and can exhibit unusually high activity. However, unlike extended surfaces, these clusters are highly fluxional, strongly isomer-dependent, and often deviate from conventional scaling relationships, making accurate activity prediction challenging. In our work, we develop a combined **DFT and machine learning (ML)** framework to uncover the **geometric origin of non-scaling behavior** in the subnanometer regime. Beyond single-intermediate adsorption, we further assess realistic ORR conditions by considering higher intermediate coverages. Thermodynamic analysis reveals a strong oxidative tendency of supported Pt clusters, favoring oxygen monolayer formation, which increases ORR overpotentials relative to bare clusters and highlights the critical role of coverage-dependent structural evolution in supported subnanometer electrocatalysts.

---

## Repository Content

This repository contains the following data and codes:

### 1) Optimized structures (Pt<sub>7–13</sub>/graphene)
For each cluster size (**Pt<sub>7</sub>, Pt<sub>8</sub>, Pt<sub>9</sub>, Pt<sub>10</sub>, Pt<sub>11</sub>, Pt<sub>12</sub>, and Pt<sub>13</sub>**), the repository provides:

- the **global minimum (GM)** structure, and  
- a set of **low-energy local minima (LMs)** structures.

All LMs included here lie within an energy window of **0.4 eV** relative to the corresponding GM.

### 2) DFT dataset
- **Excel datasheets (.xlsx)** containing the corresponding DFT-generated data.

### 3) Machine learning workflow
- **Python scripts (.py)** and/or **Jupyter notebooks (.ipynb)** used for ML model development, training, and analysis.

---

## File Formats

- **CONTCAR**: VASP-format optimized atomic coordinates for graphene-supported Pt<sub>7–13</sub> clusters (Pt cluster + graphene atoms included), suitable for direct use in **VASP**.
- **.xlsx**: processed DFT dataset used for analysis and ML model input.
- **.ipynb**: Jupyter notebooks for post-processing, ML model training, evaluation and visualization.

Please refer to the repository folder structure for the exact naming scheme and organization.

---

## Citation

If you use this dataset in your work, please cite the associated manuscript:

S. Maity#, R. K. Sharma#, H. Minhas, B. Pathak*  
**Deciphering Key Descriptors for Scaling Relationships in Graphene-Supported Ptₙ Clusters via Machine Learning**

(Citation details will be updated upon publication.)

---

## Contact

For questions or data requests:

**Biswarup Pathak** (Corresponding Author)  
Department of Chemistry, IIT Indore  
E-mail: biswarup@iiti.ac.in
