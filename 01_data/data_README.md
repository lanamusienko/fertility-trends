# 📂 **Data Folder — Overview**

This directory contains all raw and cleaned datasets used in the projectc**“Analysis of IVF Trends in the United States (2020–2022)”** for the ELO 2 at MIT Emerging Talent Program.

Data comes from the  
📌 **CDC National ART Surveillance System (NASS)** for years **2020–2022**  
🔗 https://data.cdc.gov/browse?q=Assisted+Reproductive+Technology

The folder is organized into:

- **`raw/`** — unmodified CSV files downloaded directly from CDC  
- **`clean/`** — cleaned, standardized versions used for analysis and modeling  

## 🧪 **Raw Data Files (`raw/`)**

These are the original CSV files downloaded from the CDC website.  
They are not modified in any way and serve as the source of truth for the project.

### 📂 Raw Data Contents  

#### **2020**

- [2020 ART Patient & Cycle Characteristics](raw/2020_Final_Assisted_Reproductive_Technology_(ART)_Patient_and_Cycle_Characteristics_20251127.csv)
- [2020 ART Services & Profiles](raw/2020_Final_Assisted_Reproductive_Technology_(ART)_Services_and_Profiles_20251127.csv)
- [2020 ART Summary](raw/2020_Final_Assisted_Reproductive_Technology_(ART)_Summary_20251127.csv)

#### **2021**

- [2021 ART Patient & Cycle Characteristics](raw/2021_Final_Assisted_Reproductive_Technology_(ART)_Patient_and_Cycle_Characteristics_20251127.csv)
- [2021 ART Services & Profiles](raw/2021_Final_Assisted_Reproductive_Technology_(ART)_Services_and_Profiles_20251127.csv)
- [2021 ART Summary](raw/2021_Final_Assisted_Reproductive_Technology_(ART)_Summary.csv)

#### **2022**

- [2022 ART Patient & Cycle Characteristics](raw/2022_Final_Assisted_Reproductive_Technology_(ART)_Patient_and_Cycle_Characteristics_20251127.csv)
- [2022 ART Services & Profiles](raw/2022_Final_Assisted_Reproductive_Technology_(ART)_Services_and_Profiles_20251127.csv)
- [2022 ART Summary](raw/2022_Final_Assisted_Reproductive_Technology_(ART)_Summary_20251127.csv)

## 🔧 **Cleaned Data Files (`clean/`)**

These files were processed to:

- standardize column names;  
- convert numerical fields;  
- extract meaningful IVF success metrics;  
- combine multi-year data;
- remove unusable or incomplete records.

### 📂 Clean Data Contents  

- [patient_clean.csv](clean/patient_clean.csv) - standardized patient and cycle characteristics  
- [services_clean.csv](clean/services_clean.csv) - cleaned services and clinic profiles  
- [summary_clean.csv](clean/summary_clean.csv) - cleaned summary indicators used for analysis  
- [summary_raw_2020_2022.csv](clean/summary_raw_2020_2022.csv) - combined raw subset for metric building  
