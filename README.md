# Post-Earnings Announcement Drift in the 21st Century: Evidence from US Equities

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Author**: Shreyas Urgunde  
**Date**: June 2025  
**Institution**: Warwick Business School  

---

## 📘 Overview

This repository contains the code and results for the research project *Post-Earnings Announcement Drift in the 21st Century: Evidence from US Equities*.  
The study investigates whether the PEAD anomaly continues to persist in modern US equity markets using a sample of 50 large-cap firms from 2000 to 2023.

The main finding is that the PEAD effect has significantly weakened and is largely explained by risk factors like size, value, and momentum. Once these standard controls are included, the predictive power of earnings surprises becomes statistically insignificant. This holds across both accounting-based and analyst-based (I/B/E/S) surprise measures.

---

## 📁 Project Structure

- `Data/` – Finalized CRSP, Compustat, and I/B/E/S datasets used in the paper  
- `Jupyter Notebook/` – Core analysis notebook (`5582804.ipynb`)  
- `Research Paper/` – Final PDF report  
- `Results/` – Visualizations, regression outputs, and Excel tables  

---

## 🔧 Replication Guide

### 1. 📦 Data Access

All datasets used in this project are included in the `Data/` folder for full transparency and replication.  
For updated or extended data, access to CRSP, Compustat, and I/B/E/S via WRDS or equivalent platforms may be required.

---

### 2. ⚙️ Setup Instructions

Clone the repository:

```bash
git clone https://github.com/shreyasxi/PEAD-Anomaly-in-US-Equities.git
cd PEAD-Anomaly-in-US-Equities
```

### 3. ▶️ Running the Analysis

Open and run the following Jupyter notebook from the `Jupyter Notebook/` folder:

- `5582804.ipynb` – Contains the complete workflow:
  - Data preparation  
  - Event study methodology  
  - Portfolio sorts and hypothesis testing  
  - Cross-sectional regressions  
  - Final outputs are saved to the `Results/` folder

## 📚 Citation

If you use this repository or its findings, please cite the original work:

Urgunde, S. (2025). *Post-Earnings Announcement Drift in the 21st Century: Evidence from US Equities*. Warwick Business School.

```bibtex
@mastersthesis{urgunde2025pead,
  author       = {Shreyas Urgunde},
  title        = {Post-Earnings Announcement Drift in the 21st Century: Evidence from US Equities},
  school       = {Warwick Business School, The University of Warwick},
  year         = {2025},
  month        = {June},
  note         = {Submitted in partial fulfilment of the requirements for IB93F0 Research Methodology}
}
```

