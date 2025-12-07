# 🌿 Analysis of IVF Trends in the United States (2020–2022)

## 💡 Why This Topic Matters

Infertility is a global health challenge affecting an estimated 1 in 6 couples (World Health Organization).  
As someone who personally went through the IVF journey for more than ten years and welcomed a child after multiple treatment cycles, this topic is deeply meaningful to me.

IVF results are complex, vary greatly by patient and clinic, and often difficult for people to interpret during an already emotionally heavy process.

This project aims to change that - by transforming raw U.S. CDC data into clear, accessible insights.

## 📊 What This Project Analyzes

Using official CDC ART datasets from **2020, 2021, and 2022**, the project explores:

### ✔ Clinic distribution across the U.S.  
Which states have the most IVF facilities, and where access is limited?

### ✔ IVF cycle volume trends  
How do treatment volumes shift year-to-year?

### ✔ Success rates by age  
How strongly does age impact live birth outcomes?

### ✔ Clinic-level performance  
Do clinics with higher cycle volumes produce better success?

### ✔ Predictive modeling  
Can we estimate whether a clinic is likely to achieve above-average success?

## 🔍 Key Findings

### ⭐ Age is the strongest predictor of IVF success  
Success rates decline sharply after **age 37**, aligning with medical research.

### ⭐ Clinic volume matters  
High-volume clinics tend to achieve significantly better outcomes — potentially due to experience, resources, or patient selection.

### ⭐ U.S. state differences are substantial  
Some states show consistently better outcomes, possibly influenced by insurance coverage and local policies.

### ⭐ Many IVF indicators are strongly correlated  
For example, transfer success strongly correlates with live birth rates.

## 🤖 Machine Learning Insights

To better understand which factors contribute most strongly to IVF success, the project incorporated two complementary machine learning models.

The first, a **Logistic Regression** model, helped quantify the influence of key predictors and revealed that both **age group** and **clinic volume** consistently shaped the likelihood of achieving above-average success rates.  

The second model, a **Decision Tree classifier**, offered a visually intuitive view of how these factors interact. It showed that clinics with higher treatment volumes tend to reach stronger outcomes and highlighted natural threshold splits that explain why different patient groups experience varying probabilities of success.  

Together, these models provided both statistical precision and interpretability, deepening the understanding of IVF performance patterns across clinics and patient populations.

## 🎨 Visual Storytelling

A central part of this project involved transforming complex data into clear and accessible visual narratives. The visualizations span national maps, trend curves, and model-based interpretations—each designed to highlight a different dimension of IVF care in the United States.  

A **choropleth map** illustrates how unevenly IVF clinics are distributed across states, while **age-based success rate curves** reveal the sharp decline in outcomes beginning in the late thirties. Additional visuals—such as **feature importance charts**, a **correlation heatmap**, and **cycle volume trend lines** - clarify relationships among key indicators and show which variables matter most for prediction.  

## 🔗 Data Source

📌 **CDC National ART Surveillance System (NASS)**  
https://data.cdc.gov/browse?q=Assisted+Reproductive+Technology

## 📘 About the Author

**Svitlana Musienko**  
Learners od Cohort 6 of MIT Emerging Talent Data Science
GitHub: https://github.com/lanamusienko  
Project Repo: https://github.com/lanamusienko/fertility-trends