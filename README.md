
---

### **Repository Structure**

```text
├── README.md                                   # Project overview and instructions
├── report/
│   └── CaseStudyReport.pdf                     # Final multi-page case study report
├── notebooks/
│   └── Guilan_High_Humidity_Materials.ipynb    # Full analysis and modeling workflow
├── data/
│   ├── guilan_construction_materials.xlsx                  # Unprocessed raw dataset
│   ├── guilan_construction_raw_and_norm.xlsx               # Cleaned + normalized dataset
│   └── guilan_construction_normalized_with_final_score.xlsx # Final scored dataset
```

---

## **How to Use This Repository**

This repository contains all components of the **construction material climate-suitability analysis for high-humidity environments in Guilan (Lahijan)**.

You can interact with it in the following ways:

---

### **1. Read the Final Report**

The complete, polished case study report is available at:

```
report/CaseStudyReport.pdf
```

The report includes:

* data collection & preprocessing
* feature engineering (MRI, TSI, CDS)
* exploratory data analysis (EDA)
* correlation analysis
* clustering & scoring methodology
* material ranking results
* recommendations for construction in humid climates

---

### **2. Explore the Analysis in the Jupyter Notebook**

Open:

```
notebooks/Guilan_High_Humidity_Materials.ipynb
```

This notebook contains the full analytical workflow, including:

* dataset cleaning & preprocessing
* min–max normalization
* engineered feature calculations:

  * **MRI** — Moisture Risk Index
  * **TSI** — Thermal Sensitivity Index
  * **CDS** — Construction Durability Score
* correlation matrix & visualizations
* K-Means clustering
* final scoring model & material ranking

You can run the notebook using:

* **Jupyter Notebook**
* **VS Code**
* **Google Colab**

---

### **3. Work With the Dataset**

All datasets used in this study are located in the `data/` directory.

**Files:**

* **guilan_construction_materials.xlsx**
  *Unprocessed dataset (raw measurements)*

* **guilan_construction_raw_and_norm.xlsx**
  *Clean + normalized dataset used in the notebook*

* **guilan_construction_normalized_with_final_score.xlsx**
  *Final processed dataset containing the climate suitability score for each material*

---

## **Author**

**Nikoo Najafian**
Construction Material Climate Suitability Case Study (2025)

---

