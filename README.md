# 🫁 FibroPred2 — Predictive Modeling in Pulmonary Disease

> 🧠 Hackathon 2024 | Biomedical Data Science with R  
> 📅 Date: December 13, 2024  
> 👩‍💻 Authors: Ainhoa López, Laura Llorente, Luis Carlos Ospina Restrepo  
> 📄 File: `hackathon_2024.Rmd` | Language: R / R Markdown

---

## 📌 Overview

This project was developed for a biomedical hackathon focused on predicting clinical outcomes in pulmonary disease.

Using a real anonymized hospital dataset, we explored predictors of:

- Disease progression
- Transplantation necessity
- Mortality risk

We applied logistic regression, performance evaluation metrics, and built predictive models for pulmonary function evolution (FVC and DLCO).

---

## 📁 Dataset

**File:** `pulmonar_data_marato.xlsx`  
The dataset includes:

- **Clinical variables:** biopsy markers, blood levels, diagnostics  
- **Outcome variables:**  
  - `Progressive.disease`  
  - `Necessity.of.transplantation`  
  - `Death`  
- **Pulmonary function:**  
  - `FVC (%)` and `DLCO (%)` at diagnosis and 1 year later

---

## ⚙️ Methods

- 🧮 **Logistic regression** for binary classification  
- 🎯 **Significance filtering** (`p < 0.05`)  
- 📊 **Performance metrics:**
  - Accuracy
  - Sensitivity
  - Specificity

- 📈 **Visualization techniques:**
  - Barplots of coefficients
  - Heatmaps (accuracy and significance)
  - Boxplots
  - Sensitivity/specificity stacked bars
  - Coefficient vs P-value scatter plots

- 📉 **Linear regression models** to predict FVC and DLCO at 1 year from diagnostic baseline

---

## 🔍 Key Outputs

- A table of **significant predictors** across outcomes  
- Visualizations that highlight variable relevance  
- Regression models predicting future pulmonary function

---

## 🧰 Tools & Libraries

- `tidyverse` (dplyr, tidyr, ggplot2)  
- `readxl`, `caret`, `broom`, `patchwork`  
- `knitr` for report generation

---

## 📎 How to Use

1. Clone the repository  
2. Add `pulmonar_data_marato.xlsx` to your working directory  
3. Open `hackathon_2024.Rmd` in **RStudio**  
4. Click **Knit → HTML** to generate the report

---

## 📬 Contact

If you have questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/luisbcn05) or check out more projects on [GitHub](https://github.com/luiss827).

---
