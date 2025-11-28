# Sparse Bayesian Infinite Factor Model: Applications on NIRS Data

This repository contains the code developed for my Master’s thesis:

**Sparse Bayesian Infinite Factor Model: applications on NIRS data**  
**Author:** Massimo Armano  
**University:** University of Turin (UniTo)  
**Academic year:** 2024/2025  

---

## Description

This project provides a clean and fully reproducible **educational implementation** of the  
**Sparse Bayesian Infinite Factor Model (SBIFM)**.

The purpose of this work is primarily **formative**:  
the model has been implemented step by step as part of my learning process  
in Bayesian statistics, hierarchical modeling, and MCMC computation.  
The code has been studied, developed, and refined under the guidance of my thesis advisor.

During the development, I **took inspiration from multiple sources**, including:

- the theoretical and computational material shared by **Dunson & Bhattacharya**,  
- as well as the public GitHub resources made available by **Evan Poworoznek**,  

which were extremely helpful in understanding the structure, intuition, and practical challenges of sparse Bayesian factor models.

Importantly, **no external R or Python packages implementing SBIFM or related sparse Bayesian factor models were used** for the analyses carried out in this thesis.  
All functions used for simulation, inference, and posterior analysis were developed within this project  
with an explicit educational and methodological goal.

The repository includes:

- preprocessing routines for NIRS spectral data,  
- an MCMC implementation of the SBIFM,  
- posterior summaries and diagnostics,  
- visualization tools for factor loadings, latent factors, and spectral behaviour.

---

## Applications

The implementation is first tested on **synthetic datasets**,  
with the objective of reproducing the main results of:

- Dunson & Bhattacharya (2011), *Sparse Bayesian Infinite Factor Models*.

After verifying the model behaviour on simulated data,  
the methodology is applied to two real NIRS datasets:

1. **Biscuit dough NIRS spectra**  
2. **Wheat kernel NIRS spectra**

These real-world analyses form the applied component of the thesis.

---




A possible structure:

-
