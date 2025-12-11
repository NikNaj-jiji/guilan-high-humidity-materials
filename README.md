# Construction Material Suitability in High-Humidity Environments  
_Data-driven assessment for Guilan, Iran_

## Project Overview

This project evaluates the suitability of common construction materials for the humid climate of Guilan Province (northern Iran).  
Using engineered indices, normalization, exploratory data analysis, clustering, and a moisture-dominant scoring model, the study ranks both structural and finishing materials by their climate durability.

This work was conducted as an **independent data science project** and applied directly to a real residential construction project in Lahijan, Guilan.

## Repository Structure

```text
.
├── README.md                     # Project overview and instructions
├── report/
│   └── CaseStudyReport.pdf       # Final case study report (multi-page, polished)
├── notebooks/
│   └── Guilan_High_Humidity_Materials.ipynb  # Full analysis and modeling
├── data/
│   └── guilan_construction_raw_and_norm.xlsx  # Raw + normalized materials dataset

## How to Use This Repository

This repository contains all components of the construction material climate-suitability analysis.  
You can interact with it in the following ways:

### 1. Read the Final Report
The complete case study is available in:

report/CaseStudyReport.pdf

It includes the data collection methods, feature engineering, EDA, clustering, modeling, results, and recommendations.

### 2. Explore the Analysis in Jupyter Notebook
Open: notebooks/LahijanConstructionCaseStudy.ipynb


This notebook contains:

- data preprocessing  
- min–max normalization  
- engineered feature calculations (MRI, TSI, CDS)  
- correlation analysis  
- clustering analysis  
- final scoring model and ranking  

You may run the notebook locally using Jupyter, VS Code, or Google Colab.

### 3. Work with the Dataset
The dataset used for this study is located in the data folder.
In this folder you find three datasets:
- guilan_construction_materials.xlsx --- Unprocessed dataset
- guilan_construction_raw_and_norm.xlsx --- Clean Processed dataset used in the notebook
- guilan_construction_normalized_with_final_score --- Final dataset that includes the final score for each material


