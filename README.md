# Sparse Bayesian Infinite Factor Model: Applications on NIRS Data

## Description

This project provides a clean and fully reproducible **educational implementation** of the  
**Sparse Bayesian Infinite Factor Model (SBIFM)**.

The purpose of this work is primarily **formative**:  
the model has been implemented step by step as part of my learning process  
in Bayesian statistics, hierarchical modeling, and MCMC computation.  
The code has been studied, developed, and refined under the guidance of my thesis advisor.

During the development, I **took inspiration from multiple sources**, including:

- the theoretical and computational material shared by **Dunson & Bhattacharya**,  
  available here: https://github.com/david-dunson/sparse_bayesian_infinite_factor_models  
- and the public GitHub resources made available by **Evan Poworoznek**,  
  available here: https://github.com/poworoznek/infinitefactor  

These resources were extremely helpful in understanding the structure, intuition,  
and practical challenges of sparse Bayesian factor models.

Importantly, **no external R or Python packages implementing SBIFM or related sparse Bayesian factor models were used** for the analyses carried out in this thesis.  
All functions used for simulation, inference, and posterior analysis were developed within this project  
with an explicit educational and methodological goal.

---

## Repository Contents

The repository is organised into the following main components:

### **1. R Code (`/R`)**

This folder contains all the R scripts used in the thesis, including:

- **SBIFM complete with replication**  
  Full implementation of the Sparse Bayesian Infinite Factor Model for *simulated data*,  
  including MCMC sampling, adaptive factor selection, mixing evaluation,  
  covariance estimation, prediction assessment, and performance metrics.

- **Warm start SBIFM**  
  Version of the model using warm-start initialisation, useful for faster convergence  
  or when applying the model to real datasets.

- **NIRS biscuit preprocess**  
  Preprocessing pipeline for the *publicly available* biscuit dough NIRS dataset,  
  including centering, scaling, feature inspection, and spectral cleaning.

- **Mixing Plot**  
  Functions and scripts for traceplots, autocorrelation analysis,  
  effective sample size estimation, and general MCMC diagnostic plots.

- **Results Plot**  
  Scripts to generate visualisations of posterior loadings, covariance estimates,  
  fitted vs predicted values, beta coefficients, and factors extracted from NIRS data.

- **More analysis**  
  Additional utilities, diagnostic checks, and extended analyses performed  
  during model development and experimentation.

---

### **2. LaTeX Material (`/Latex`)**

This directory includes the LaTeX sources related to the thesis:

- **Latex Thesis**  
  LaTeX document and structure used for writing the full thesis manuscript.

- **Presentation Latex**  
  Slides and presentation structure for the thesis defence,  
  formatted in LaTeX (likely Beamer).

---

### **3. License and Documentation**

- **LICENSE**  
  Currently set to MIT License, allowing reuse with attribution.

- **README.md**  
  The file you are reading.

---

## Notes on Data Usage

Only **public datasets** (such as the biscuit dough NIRS data) are included or referenced in this repository.  
The wheat kernel NIRS dataset used in the applied section of the thesis is **private**  
and therefore **not included** in this repository.

---

## References

- Dunson, D. B., & Bhattacharya, A. (2011). *Sparse Bayesian Infinite Factor Models*. **Biometrika**, 98(2), 291–306.  
- Poworoznek, E. (GitHub repository): https://github.com/poworoznek/infinitefactor  
- Additional references are included in the thesis manuscript.

---

## Citation

If you use or refer to this project, please cite the thesis and this repository.  
A `CITATION.cff` file will be included to enable automatic GitHub citation.
