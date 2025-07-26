# 📊 Post-Earnings Announcement Drift in the 21st Century: Evidence from US Equities

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

- `Data/` – Merged and cleaned data from CRSP, Compustat, and I/B/E/S  
- `Jupyter Notebook/` – Final analysis notebooks  
- `Research Paper/` – Final PDF report  
- `Results/` – Charts, figures, and Excel sheets from the analysis  

---

## 🔧 Replication Guide

### 1. 📦 Data Requirements

This project uses proprietary financial datasets, which are not redistributed in this repo. To replicate the analysis, you will need access to:

- **CRSP**: Daily stock return data  
- **Compustat**: Quarterly earnings data (EPS, RDQ)  
- **I/B/E/S**: Analyst earnings forecasts  

---

### 2. ⚙️ Setup Instructions

Clone the repository:

```bash
git clone https://github.com/shreyasxi/PEAD-Anomaly-in-US-Equities.git
cd PEAD-Anomaly-in-US-Equities
