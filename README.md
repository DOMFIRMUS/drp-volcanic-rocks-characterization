# 🪨 Digital Rock Physics (DRP): Characterization of Volcanic and Carbonate Rocks

This repository contains the official Python implementation and computational framework for the Master's thesis: **"Characterization of Volcanic and Carbonate Rocks through X-Ray Microtomography Image Analysis using PoreSpy, OpenPNM, and Machine Learning"**.

Developed at the **Graduate Program in Energy and Nuclear Technologies (PPGTEN)** - Federal University of Pernambuco (UFPE).

## 📋 Overview
This project provides a robust pipeline for the petrophysical characterization of complex porous media. By utilizing **X-Ray Microtomography**, the framework enables the transition from raw 3D images to advanced transport properties (Relative Permeability and Capillary Pressure) using **Pore Network Modeling (PNM)**.

## 🚀 Key Features
* **3D Image Pre-processing:** Automated stitching/mosaicking of slices and denoising via 3D Median Filters.
* **3D Segmentation:** Automatic thresholding (Otsu's method) and ROI (Region of Interest) heterogeneity analysis.
* **Pore Network Modeling (PNM):** * Pore network extraction using **PoreSpy**.
    * Two-phase flow simulations (Primary Drainage) using **OpenPNM**.
* **Statistical Validation:** Comparative analysis between Digital Rock Physics (DRP) results and experimental ground truths (Helium Porosimetry and Gravimetry).

## 📊 Data Access (Zenodo)
**Note:** This repository contains **only the source code**. Due to the large size of the raw 3D images (TIFF format, 40 microm resolution) and experimental tables, the full dataset is hosted on Zenodo.

## 🛠 Tech Stack
* **Language:** Python 3.10+
* **Physics/Imaging:** `PoreSpy`, `OpenPNM`, `Scikit-image`, `Tifffile`.
* **Data Analysis:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`.

## 📖 Citation
If you use this code or the associated dataset in your research, please cite:

> Cardoso, J. F., Antonino, A. C. D., & Reichert, J. M. (2026). **Caracterização de Rochas Vulcânicas e Carbonáticas por Meio da Análise de Imagens de Microtomografia de Raios X Utilizando PoreSpy, OpenPNM e Aprendizagem de Máquina** (1.0.0) [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.18750641](https://doi.org/10.5281/zenodo.18750641)

## 🤝 Acknowledgments
The author acknowledges the financial and institutional support from:
* **PRH 48.1 - ANP/FINEP** (Process: 48610.201019/2019-38)
* **UFPE** (Department of Nuclear Energy - DEN)
* **CRCN-NE / CNEN**
* **FADE-UFPE**
* **CAPES / CNPq**

---
*Developed by Jean Firmino Cardoso as part of the Master's Degree requirements.*
