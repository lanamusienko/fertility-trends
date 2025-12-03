# 📊 Analysis & Visualizations

This folder contains the Jupyter notebooks used for data cleaning, exploratory analysis, visualization, and machine learning modeling for the project **“Analysis of IVF Trends in the United States (2020–2022)”**. The files are organized to reflect the natural workflow: loading raw data, cleaning and preparing datasets, exploring patterns, building models, and analyzing correlations.

---

## 🔎 Files Overview

📁 **01_load_and_explore**  
This file loads the raw CDC ART CSV files from the `01_data/raw/` folder and performs an initial inspection of their structure. It previews the data frames, checks column names and types, and verifies that all required files for the years 2020–2022 are present. The goal is to understand what information is available before any cleaning or transformation.

🧼 **02_clean_data**  
This file focuses on cleaning and preparing the summary data. It standardizes column names, converts numeric fields that contain commas or symbols, removes non-analytic text and footnote markers, and combines the multi-year summary files into a single dataset. The cleaned outputs are saved as `summary_clean.csv` and `summary_raw_2020_2022.csv` in `01_data/clean/` and form the core dataset for later analysis.

🧬 **03_clean_patient**  
This file processes the “Patient & Cycle Characteristics” data. It cleans numeric columns, aligns year information, and keeps only the variables that are relevant for understanding patient age groups and cycle characteristics. The result is a tidy version of patient-level characteristics saved as `patient_clean.csv`, which can be linked conceptually to the summary dataset.

🏥 **04_clean_services**  
This file cleans the “Services & Profiles” dataset, which describes clinic services and structural characteristics. It standardizes service indicators, harmonizes text categories, and prepares clinic-level features that can be used to understand how service offerings relate to volume and outcomes. The cleaned services data is saved as `services_clean.csv`.

📈 **05_analysis_visuals**  
This file contains the main exploratory data analysis and visualizations. It examines IVF cycle volumes over time, shows how clinics are distributed across U.S. states, and explores success rates by age group. It also produces key figures such as line charts for success trends and the U.S. map of IVF clinics. Many of the plots used in the final presentation come from this notebook.

🤖 **06_ml_live_birth_model**  
This file builds machine learning models to predict high IVF success at the clinic-year level. It constructs a feature set from the cleaned data, creates a binary target for “above-average” live-birth success, and trains both a Logistic Regression model and a Decision Tree classifier. It evaluates performance on a test set and examines feature importance, with a particular focus on age group, clinic volume, and state.

🔥 **07_correlation_analysis**  
This file restructures the data into a wide format so that multiple IVF indicators can be analyzed together. It carefully converts all metric columns to numeric format, computes a correlation matrix, and visualizes it as a heatmap. This helps reveal how key success metrics, discontinuation rates, and cycle counts are related to each other across clinics and years.

---

## 📂 Files Links - Quick Access

- [01_load_and_explore.ipynb](01_load_and_explore.ipynb)  
- [02_clean_data.ipynb](02_clean_data.ipynb)  
- [03_clean_patient.ipynb](03_clean_patient.ipynb)  
- [04_clean_services.ipynb](04_clean_services.ipynb)  
- [05_analysis_visuals.ipynb](05_analysis_visuals.ipynb)  
- [06_ml_live_birth_model.ipynb](06_ml_live_birth_model.ipynb)  
- [07_correlation_analysis.ipynb](07_correlation_analysis.ipynb)  
