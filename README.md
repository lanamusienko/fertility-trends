# 🌱 Analysis of IVF Trends in the United States (2020–2022)

### *A Data Science Capstone Project — MIT Emerging Talent Program*

## ✨ Why This Project Matters

Infertility touches millions of lives - 1 in 6 couples worldwide, according to the WHO.  
Behind every statistic is a very real emotional journey filled with uncertainty, hope, and courage.

For me, this topic is deeply personal.  
I spent over 10 years trying to become pregnant, went through multiple IVF cycles,  
and finally welcomed my first child after a long, difficult process.  
Because of that experience, I understand how *confusing*, *overwhelming*, and *technically complex* IVF data and clinic outcomes can be for patients making life-changing decisions.

This project is not just an academic exercise - it is a way to:

- 💛 Bring clarity to a sensitive but important healthcare process  
- 📊 Transform complex clinical datasets into meaningful insights  
- 🩺 Support women and families navigating fertility treatment  
- 🌍 Highlight inequities in access and success across U.S. states  
- 🧠 Apply real-world data science to a topic that genuinely impacts lives  

This project aims to turn raw CDC data into **clear, visual, and actionable insights** that support more informed reproductive healthcare decisions.

## 🎯 Project Goals

### 🔍 Analytical Goals

- ✔ Clean and integrate CDC ART Data (2020–2022)  
- ✔ Analyze clinic distribution and patient cycle patterns  
- ✔ Evaluate IVF success rates across age groups  
- ✔ Compare clinic-level and state-level performance  
- ✔ Build ML models predicting high IVF success probability  
- ✔ Visualize correlations across key IVF metrics  

### 🧪 Learning Goals

- ✔ Practice data cleaning, wrangling, merging  
- ✔ Conduct EDA & statistical analysis  
- ✔ Build Logistic Regression & Decision Tree models  
- ✔ Create professional static + interactive charts  
- ✔ Strengthen storytelling + communication  
- ✔ Deliver a polished portfolio-ready project  

## 📁 Data Sources

All data comes from the **CDC National ART Surveillance System (NASS)**.

- **Years included:** 2020, 2021, 2022  
- **Key files:**
  - ART Services & Profiles  
  - ART Patient & Cycle Characteristics  
  - ART Summary Tables  

**Folder locations:**

- 📂 Raw files: `01_data/raw/`  
- 📂 Cleaned files: `01_data/clean/`  

## 🧰 Methods Overview

### 🧹 Data Cleaning

The raw CDC datasets contained mixed formats, text-heavy fields, and inconsistent numeric formatting.  
Cleaning steps included:

- Converting all column names to a standardized format  
- Removing non-analytic free-text fields (addresses, director names, etc.)  
- Parsing numeric values (removing commas, symbols, and footnote markers)  
- Filtering out rows without measurable clinical outcomes  
- Normalizing age groups and categorical labels  
- Merging multi-year datasets into a unified structure  
- Creating derived features such as clinic volume and success indicators  

### 📊 Exploratory Data Analysis

Exploratory analysis focused on identifying major trends in IVF access, clinic performance, and success outcomes.  
Key analytical components:

- Distribution of IVF clinics across U.S. states  
- National IVF cycle volume changes (2020–2022)  
- Success rate trends by age group (<35, 35–37, 38–40, >40)  
- Comparison of clinic-level performance metrics  
- Geographic variation in access and outcomes  
- Correlation heatmap of major clinical indicators  

This stage provided the foundation for selecting meaningful features for modeling.

### 🤖 Machine Learning

Two supervised learning models were built to explore predictors of high live-birth success:

#### **1️⃣ Logistic Regression**
Used to estimate the probability that a clinic-year achieves **above-average live-birth success**.

Features included:
- Clinic volume  
- Age group  
- State  
- Year  

Insights:
- Clinic volume was one of the strongest predictors  
- Age group significantly influenced expected success  
- State-level differences contributed meaningful signal  

#### **2️⃣ Decision Tree Classifier**
Used primarily for **model interpretability** and understanding feature importance.

Outputs:
- Ranked feature importance list  
- Explanation of which variables most strongly drive the prediction  
- Visual insights into relationships between volume, age, and success rates  

Together, these modeling methods demonstrate practical applications of:
- Feature engineering  
- Binary classification  
- Data-driven interpretation  
- Healthcare analytics  

This aligns closely with the technical competencies emphasized in the MIT Emerging Talent program.

## ⭐ Key Insights

From the combined cleaning, analysis, visualization, and modeling, several key findings emerged:

- **IVF success declines sharply after age 37**, with the largest drop after 40  
- **Clinics with higher annual cycle volumes consistently achieve better outcomes**  
- **State-level differences** show meaningful variation in both access and clinic performance  
- Strong correlations exist between:
  - retrieval → transfer → live-birth success  
  - clinic volume → cycle outcomes  
- Machine learning confirms volume and age group as **top predictors** of high success probability  
- Some indicators show near-zero correlation, revealing independent patterns in treatment outcomes  

These insights help illuminate hidden patterns in IVF care, inform patient choices, and encourage further research in reproductive health analytics.

---

## 📬 Contact

**Author:** Svitlana Musienko  
**Program:** MIT Emerging Talent — Data Science  
**GitHub:** https://github.com/lanamusienko  
**Project Repository:**[fertility-trends](https://github.com/lanamusienko/fertility-trends).
