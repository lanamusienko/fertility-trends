# 📊 Analysis & Visualizations

This folder contains files used for **data cleaning**,  
**exploratory analysis**, **visualization**, and **machine learning modeling** for the project  
**“Analysis of IVF Trends in the United States (2020–2022)”**.

Files are organized in the exact sequence of the analytical workflow,  
from loading the data to building predictive models.

---

## 📁 Folder Contents

## 1️⃣ **01_load_and_explore.ipynb**

**Purpose:**  
- Load raw CDC datasets  
- Inspect structure, columns, datatypes  
- Verify file completeness  
- Initial exploration before cleaning  

**Key Outputs:**  
- List of raw files loaded  
- Preview of data frames  
- Basic understanding of available metrics  

## 2️⃣ **02_clean_data.ipynb**
**Purpose:**  
- Clean and standardize **Summary** data (main dataset)  
- Fix column names  
- Convert numeric fields  
- Remove footnotes, symbols, and text artifacts  
- Combine multi-year summary datasets  

**Key Outputs:**  
- `summary_clean.csv`  
- `summary_raw_2020_2022.csv`

## 3️⃣ **03_clean_patient.ipynb**
**Purpose:**  
- Clean **Patient & Cycle Characteristics** data  
- Standardize numeric columns  
- Fix date/year formats  
- Select analytically relevant fields  

**Key Outputs:**  
- `patient_clean.csv`  

## 4️⃣ **04_clean_services.ipynb**
**Purpose:**  
- Process **Clinic Services & Profiles** dataset  
- Clean and standardize service categories  
- Extract clinic-level features  

**Key Outputs:**  
- `services_clean.csv`  

## 5️⃣ **05_analysis_visuals.ipynb**
**Purpose:**  
Full exploratory data analysis (EDA), including:

- IVF cycle volume by year  
- Clinic count by state  
- U.S. state choropleth map of clinic distribution  
- Success rates by age group  
- Multi-year trend visualization  
- Interpretation of key metrics  

**Key Outputs:**  
- All charts for the Results & Presentation section  

## 6️⃣ **06_ml_live_birth_model.ipynb**
**Purpose:**  
Machine learning modeling to predict high IVF success.

Methods used:
- Logistic Regression  
- Decision Tree Classifier  

Tasks performed:
- Feature engineering  
- Train-test split  
- Model training & evaluation  
- Feature importance analysis  

**Key Outputs:**  
- Model performance metrics  
- Feature importance plots  

## 7️⃣ **07_correlation_analysis.ipynb**
**Purpose:**  
- Compute correlations across all success indicators  
- Clean metric fields for numeric correlation  
- Generate correlation heatmap  
- Identify relationships among IVF performance metrics  

**Key Outputs:**  
- Correlation heatmap  
- Ranked correlation insights for presentation  

---

## 🔗 Files Links

If viewing this file on GitHub, use these direct links:

- [01_load_and_explore.ipynb](01_load_and_explore.ipynb)  
- [02_clean_data.ipynb](02_clean_data.ipynb)  
- [03_clean_patient.ipynb](03_clean_patient.ipynb)  
- [04_clean_services.ipynb](04_clean_services.ipynb)  
- [05_analysis_visuals.ipynb](05_analysis_visuals.ipynb)  
- [06_ml_live_birth_model.ipynb](06_ml_live_birth_model.ipynb)  
- [07_correlation_analysis.ipynb](07_correlation_analysis.ipynb)  
