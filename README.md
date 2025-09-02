# Unveiling Hidden Risk Factors in Global Markets using Principal Component Analysis
# Unveiling Hidden Risk Factors in Global Markets using PCA

This repository contains the research report **"Unveiling Hidden Risk Factors in Global Markets using PCA"**, which applies **Principal Component Analysis (PCA)** to global equity sector returns in order to uncover common market drivers, quantify risk exposures, and provide insights for portfolio management.

---

##  Overview

Financial markets are often driven by hidden common factors that affect multiple sectors simultaneously. This report demonstrates how **PCA** can extract these factors, measure their explanatory power, and provide actionable insights for **risk management** and **factor investing**.

The analysis covers:
- Extraction of common market factors  
- Quantification of variance explained by leading components  
- Visualization of loadings, scores, and rotations  
- Reconstruction of sector returns using limited factors  
- Implications for portfolio risk management  

---

##  Key Findings

- **One dominant systemic factor (PC1)** explains ~65% of variance, representing broad global market risk.  
- **A secondary factor (PC2)** explains ~15% of variance and captures **cyclical vs defensive sector rotation**.  
- **Three components together explain >85%** of return variability, sufficient for risk modeling.  
- **Reconstructed returns** using just 3 factors closely track original returns with <5% error.  
- Insights can be applied for **hedging strategies, risk decomposition, and factor-tilted investing**.  

---

##  Visuals in the Report

- **Scree Plot** – variance explained by each component  
- **PC1 Time Series** – the market factor evolution  
- **Biplot (PC1–PC2)** – sector relationships in factor space  
- **Heatmap of Loadings** – contribution of sectors to PCs  
- **Scores Scatter Plot** – market shocks and sector rotations  
- **Correlation Circle** – inter-sector relationships on PC1–PC2  
- **Return Reconstruction Charts** – comparing actual vs PCA-based returns  

---

##  Concepts Used

Some of the key statistical and financial concepts in the report include:

- [Principal Component Analysis (PCA)](#1-principal-component-analysis-pca)  
- [Principal Components (PCs)](#2-principal-components-pcs)  
- [Variance Explained](#3-variance-explained)  
- [Scree Plot](#4-scree-plot)  
- [Loadings](#5-loadings)  
- [Scores](#6-scores)  
- [Biplot](#7-biplot)  
- [Correlation Circle](#8-correlation-circle-loading-plot)  
- [Factor Rotation](#9-factor-rotation)  
- [Reconstruction](#10-reconstruction)  
- [Common Market Factor](#11-common-market-factor)  
- [Sector Rotation Factor](#12-sector-rotation-factor)  
- [Systemic Risk](#13-systemic-risk)  
- [Idiosyncratic Risk](#14-idiosyncratic-risk)  
- [Hedging](#15-hedging)  
- [Factor Investing](#16-factor-investing)  



---

##  Tools & Methods

- **Python Libraries**:  
  - `pandas` – data handling  
  - `numpy` – numerical computation  
  - `scikit-learn` – PCA decomposition  
  - `matplotlib` / `seaborn` – visualization  

- **Methodology**:  
  1. Collect sector-level return data  
  2. Standardize the dataset  
  3. Apply PCA to extract components  
  4. Visualize loadings, scores, and variance explained  
  5. Reconstruct returns with leading components  
  6. Interpret components in financial terms  



