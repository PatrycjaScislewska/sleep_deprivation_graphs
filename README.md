# Sleep deprivation and graphs

This repository contains code and data related to **graph-theoretical** and **manifold learning** analyses of fMRI data.

In this within-subject resting-state fMRI study, we examined how **acute total sleep deprivation (TSD)** and **chronic sleep restriction (CSR)** alter intrinsic functional brain organization in 28 healthy adults scanned under three conditions: **rested wakefulness (RW)**, **after one night of TSD**, and **after five nights of CSR**.

To quantify network-level disruption, we applied **graph-theoretical analyses**, including a novel **within-subject adaptation of the Hub Disruption Index (HDI)** and **Covariate-Constrained Manifold Learning (CCML)** — an unsupervised embedding technique sensitive to subject-level covariates. Moreover, we assessed **subjective sleep quality**, **sleepiness**, and **circadian traits**.

---

### Full description of the study - preprint

**“Divergent disruption of brain networks following total and chronic sleep loss: a longitudinal fMRI study”**  
*Patrycja Scislewska, Arturo Cabrera Vazquez, Iwona Szatkowska, Halszka Kontrymowicz-Ogińska, Sophie Achard, Aleksandra Domagalik*  
*bioRxiv*, 2025.10.10.681651  
[https://doi.org/10.1101/2025.10.10.681651](https://doi.org/10.1101/2025.10.10.681651)

---

### Repository Contents

- Code for quality check of data,
- Scripts for calculating **nodal** and **global graph metrics**,
- Code for **computation and validation** of the **within-subject Hub Disruption Index (HDI)**,
- Code for **Covariate-Constrained Manifold Learning (CCML)**,
- Scripts for generating **chord plots** to visualize connectivity patterns,
- Code for analysis of subjective sleep-related measures.

Additionally, this repository includes:
- Documentation of the **modified AAL** and **modified AICHA** atlases used in the analyses,
- **Preprocessed ROI time series** extracted from fMRI data

  All preprocessing steps of raw fMRI data can be fully reproduced using the following repository:  
[https://github.com/veronicamunoz/rs_graph_processing](https://github.com/veronicamunoz/rs_graph_processing)
All results described in the preprint can be fully reproduced using this repository.
---



