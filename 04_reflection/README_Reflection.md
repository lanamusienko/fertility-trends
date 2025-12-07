# 🌿 Final Reflection / Capstone Retrospective  
*MIT Emerging Talent – Data Science Program*  
*Project: Analysis of IVF Trends in the United States (2020–2022)*  

## 🔹 Introduction
This capstone project represents both a technical milestone and a personal journey. I chose to analyze IVF trends in the United States because infertility is a topic that deeply affects many people-including myself. After more than a decade of struggling with infertility and undergoing multiple IVF cycles before welcoming my first child, I understand how confusing, overwhelming, and emotionally heavy this process can be. Data often feels inaccessible or difficult to interpret for the average patient, especially at a time when clear information is most needed.

For this reason, transforming raw CDC data into meaningful insights became not just an academic exercise, but a way to elevate an important public health topic. This project allowed me to apply the full spectrum of skills I gained in the MIT Emerging Talent Data Science program—data cleaning, statistical reasoning, machine learning, visualization, and storytelling—toward something that matters both personally and socially.

## 🔹 Were the Original Project Objectives Achieved?

Partially and ultimately, successfully.  
My initial objective was to analyze global IVF trends, comparing outcomes, access, and success rates across different countries. However, very early in the process I discovered a major challenge: reliable, complete, and standardized raw IVF data simply does not exist for most countries. Many nations do not publish detailed reproductive datasets, others release only aggregated summaries, and international definitions of “success rate” vary significantly. Because of these limitations, a true global analysis was not feasible.

Recognizing this, I refined my project scope to focus on the United States, where the CDC publishes one of the world’s most comprehensive and standardized ART datasets. This shift allowed me to properly achieve my analytical goals.

Within the U.S. scope, I successfully met the objectives of the project. I cleaned and integrated all three major CDC datasets (Summary, Patient & Cycle Characteristics, and Services & Profiles), merged multi-year records, and produced clear and informative visualizations. I analyzed:

- clinic distribution across states  
- yearly IVF cycle volumes  
- success rates by age group  
- correlations between key IVF metrics  
- predictors of high IVF success using machine learning  

I also built two ML models—**Logistic Regression** and a **Decision Tree Classifier**—to evaluate which factors most strongly influence success probability.

Beyond the analytical tasks, I achieved my personal learning goals:  
Working with complex, messy real-world health data; applying statistical and exploratory techniques; implementing ML models; and communicating results clearly through visuals and storytelling.

## 🔹 Most Valuable Learning From the Project
The most valuable learning experience was understanding the complexity and imperfection of real-world data. Unlike structured coursework datasets, the CDC IVF tables contained inconsistencies, duplicate fields, non-standard numeric formats, ambiguous labels, and overlapping indicators. Cleaning and structuring this data required patience, careful reasoning, and step-by-step debugging.

This process deepened my understanding of:

- how messy health data can be  
- the importance of rigorous preprocessing  
- the need to validate assumptions at each stage  
- the impact of data preparation on model performance  

Additionally, creating meaningful visualizations—choropleth maps, line charts, correlation heatmaps, ML feature importance plots—strengthened my skills in data storytelling and helped me communicate insights in a way that is accessible to non-technical audiences.

---

## 🔹 If This Were a Team Project: What Would I Delegate?
Since this was an individual project, I carried out every step myself—from data cleaning to analysis, modeling, and visualization. Through this project, I realized how much I enjoy leading the analytical direction and ensuring that insights are clear, ethical, and meaningful.

## 🔹 Navigating the Project Management Process
Managing this project required balancing multiple components:

- understanding complex domain data  
- cleaning and merging large files  
- creating a structured repository  
- maintaining consistent naming conventions  
- version-controlling large datasets using Git LFS  
- building multiple analysis notebooks  
- exporting visualizations  
- preparing a polished presentation  

I used a structured workflow that included:

1. Defining the project scope  
2. Setting up a clear GitHub structure (`data`, `analysis_visuals`, `results_presentation`, `reflection`)  
3. Completing cleaning fils before beginning any analysis  
4. Designing charts early to guide the story  
5. Implementing ML models after establishing strong feature engineering  
6. Saving results in dedicated folders for easy retrieval  

One of the most helpful lessons was learning how to refactor and reorganize the repository when necessary. Proper structure became essential for clarity and future reproducibility.

## 🔹 Choosing the Public-Facing Artifact
I chose to create:

- a GitHub repository with all code, notebooks, and results  
- a visual PDF presentation for MIT submission  

## 🔹 Most Useful Elements of the Emerging Talent Program

When I started the MIT Emerging Talent program, I had no prior experience with Python, data analysis, or machine learning. Every step—from writing my first line of code to understanding statistical models—was new. The program provided exactly the structure and support I needed to grow from a complete beginner into someone capable of completing an independent data science project.

Several elements of the program were essential in helping me build the skills required for this capstone:

- **Foundations & Python Programming:** gave me the core skills to clean, transform, and analyze real datasets.  
- **Data Wrangling & Preprocessing:** taught me how to work with messy, inconsistent clinical data and prepare it for analysis.  
- **Workshops:** helped me design clear, interpretable charts and communicate insights effectively.  
- **AI Learning Modules:** introduced me to classification models, feature importance, model evaluation, and interpretation.  
- **Probability & Statistical Reasoning:** guided my understanding of IVF indicators, correlations, and meaningful comparisons.  
- **Project Organization Workshops:** enabled me to structure a multi-step workflow in a professional, reproducible way.  

Altogether, these components not only gave me the technical skills but also the confidence to take on a complex, open-ended project on my own—something that would have felt impossible when I first entered the program.

## 🔹 Final Thoughts
This project was more than a technical exercise—it was an opportunity to connect data science with a deeply personal experience. IVF is a journey filled with uncertainty, emotional highs and lows, and difficult decisions. By transforming complex clinical datasets into clear and actionable insights, I hope to help others make more informed choices and better understand the landscape of reproductive medicine.

Completing this capstone solidified my interest in applying data science to healthcare and women’s health. It also showed me how powerful data storytelling can be when grounded in purpose, empathy, and strong analytical foundations.

I'm proud of this project, grateful for the learning journey, and excited to continue developing as a data scientist.
