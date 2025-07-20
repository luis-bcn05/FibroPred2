# FibroPred2
🧬 Hackathon 2024 — Predictive Modeling in Pulmonary Disease

Date: December 13, 2024
Authors: Ainhoa López, Laura Llorente, Luis Carlos Ospina Restrepo
Language: R / RMarkdown
File: hackathon_2024.Rmd
🔍 Project Overview

This project was developed for a biomedical hackathon focused on predicting clinical outcomes in pulmonary diseases. Using a real anonymized dataset from a hospital cohort, we analyzed potential predictors of disease progression, need for transplantation, and mortality. The analysis included logistic regression, statistical inference, model performance evaluation, and predictive modeling of lung function metrics.
📂 Data

The dataset (pulmonar_data_marato.xlsx) includes:

    Clinical variables (e.g., biopsy markers, blood levels, diagnostics)

    Outcome variables:

        Progressive.disease

        Necessity.of.transplantation

        Death

    Pulmonary function variables:

        FVC (%) and DLCO (%) at diagnosis and 1 year after

⚙️ Methods

    Logistic Regression for binary outcome prediction

    Variable Significance Filtering via p-values (< 0.05)

    Performance Metrics:

        Accuracy

        Sensitivity

        Specificity

    Visualizations:

        Barplots of coefficients

        Heatmaps of accuracy and p-values

        Boxplots and stacked bars for metrics across outcomes

    Predictive Modeling:

        Linear regression to predict FVC and DLCO 1 year after diagnosis based on initial values

📊 Key Outputs

    Identification of significant predictors associated with poor outcomes.

    Accuracy stratified by outcome and predictor.

    Predictive models for future FVC and DLCO using initial diagnostics.

📈 Visualizations

The project includes the following plots:

    Coefficient distributions

    P-value vs Coefficient scatter plot

    Heatmaps of accuracy and statistical significance

    Sensitivity/Specificity by outcome

    Boxplots of accuracy distribution

🧪 Tools & Packages

This analysis was conducted in R, using:

    dplyr, tidyr, broom, ggplot2, caret, patchwork

    readxl for Excel import

    knitr for rendering

📁 Output

    Interactive HTML report generated with R Markdown

    Summary table of significant predictors

    Plots illustrating model insights

    Predicted values of FVC and DLCO at one-year follow-up

📌 How to Run

    Place pulmonar_data_marato.xlsx in your project folder.

    Open hackathon_2024.Rmd in RStudio.

    Knit to HTML.

🤝 Acknowledgments

This project was built as part of a student hackathon to apply real-world data science to biomedical challenges.
