# 📊👣 Analysis of IVF Trends in the United States (2020–2022) 🗽

### *A Data Science Capstone Project - MIT Emerging Talent Program*

## ✨ Why This Project Matters

Infertility touches millions of lives - 1 in 6 couples worldwide, according to the WHO.  
Behind every statistic is a very real emotional journey filled with uncertainty, hope, and courage.

For me, this topic is deeply personal.  
I spent over 10 years trying to become pregnant, went through multiple IVF cycles, and finally welcomed my first child after a long, difficult process.  
Because of that experience, I understand how *confusing*, *overwhelming*, and *technically complex* IVF data and clinic outcomes can be for patients making life-changing decisions.

This project is not just an academic exercise - it is a way to:

💛 bring clarity to a sensitive but important healthcare process;
📊 transform complex clinical datasets into meaningful insights;
🩺 support women and families navigating fertility treatment;
🌍 highlight inequities in access and success across U.S. states;  
🧠 apply real-world data science to a topic that genuinely impacts lives.  

This project aims to turn raw CDC data into clear, visual, and actionable insights that support more informed reproductive healthcare decisions.

## 🎯 Project Goals

### 🔍 Analytical Goals:

✔ clean and integrate CDC ART Data (2020–2022);  
✔ analyze clinic distribution and patient cycle patterns;  
✔ evaluate IVF success rates across age groups;
✔ compare clinic-level and state-level performance;  
✔ build ML models predicting high IVF success probability;  
✔ visualize correlations across key IVF metrics.

### 🧪 Learning Goals:

✔ practice data cleaning, wrangling, merging;  
✔ conduct EDA and statistical analysis;
✔ build Logistic Regression and Decision Tree models;  
✔ create professional static and interactive charts;  
✔ deliver a polished portfolio-ready project.  

## 📁 Data Sources

All data comes from the **CDC National ART Surveillance System (NASS)**.

**Years included:** 2020, 2021, 2022  
**Key files:**
- Assisted Reproductive Technology (ART) Services & Profiles
- Assisted Reproductive Technology (ART) Patient & Cycle Characteristics  
- Assisted Reproductive Technology (ART) Summary Tables  

**Folder locations:**

- 📂 Raw files: `01_data/raw/`  
- 📂 Cleaned files: `01_data/clean/`  

## 🧰 Methods Overview

### 🧹 Data Cleaning

The raw CDC datasets contained mixed formats, text-heavy fields, and inconsistent numeric formatting.  
Cleaning steps included:

- converting all column names to a standardized format;
- removing non-analytic free-text fields (addresses, director names, etc.);
- parsing numeric values (removing commas, symbols, and footnote markers);
- filtering out rows without measurable clinical outcomes;
- normalizing age groups and categorical labels;
- merging multi-year datasets into a unified structure;
- creating derived features such as clinic volume and success indicators.

### 📊 Exploratory Data Analysis

Exploratory analysis focused on identifying major trends in IVF access, clinic performance, and success outcomes.
Key analytical components:

- distribution of IVF clinics across U.S. states;  
- national IVF cycle volume changes (2020–2022);
- success rate trends by age group (<35, 35–37, 38–40, >40);  
- comparison of clinic-level performance metrics;
- geographic variation in access and outcomes;
- correlation heatmap of major clinical indicators.

### 🤖 Machine Learning

Two learning models were built to explore predictors of high live-birth success:

#### **1️⃣ Logistic Regression**
Used to estimate the probability that a clinic-year achieves above-average live-birth success.

Features included: clinic volume, age group, state, year.  

Insights:
- clinic volume was one of the strongest predictors;
- age group significantly influenced expected success;
- state-level differences contributed meaningful signal.

#### **2️⃣ Decision Tree Classifier**
Used primarily for model interpretability and understanding feature importance.

Outputs:
- ranked feature importance list;
- explanation of which variables most strongly drive the prediction;
- visual insights into relationships between volume, age, and success rates.  

## ⭐ Key Insights

From the combined cleaning, analysis, visualization, and modeling, several key findings emerged:

- IVF success declines sharply after age 37, with the largest drop after 40;
- Clinics with higher annual cycle volumes consistently achieve better outcomes;
- State-level differences show meaningful variation in both access and clinic performance;
- Strong correlations exist between:
  - retrieval → transfer → live-birth success  
  - clinic volume → cycle outcomes  
- Machine learning confirms volume and age group as top predictors of high success probability;
- Some indicators show near-zero correlation, revealing independent patterns in treatment outcomes.  

These insights help illuminate hidden patterns in IVF care, inform patient choices, and encourage further research in reproductive health analytics.

---

## 📬 Contact

**Author:** Svitlana Musiienko  
**Program:** MIT Emerging Talent - Data Science  
**GitHub:** https://github.com/lanamusienko  
**Project Repository:**[fertility-trends](https://github.com/lanamusienko/fertility-trends).
