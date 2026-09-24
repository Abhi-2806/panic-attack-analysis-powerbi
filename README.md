# 🧾 Panic Attack Analysis – Healthcare & Disease

_Analyzing Panic Attack in patients on the basis of Gender, Trigger reason and Medical history using Snowflake as database , SQL & Power BI._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#health-problem">Health Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

An interactive Power BI dashboard designed to analyze patterns, risk factors, and demographic trends associated with panic attack occurrences. The project transforms raw clinical/survey data into actionable insights through dynamic visualizations, KPI cards, and cross-filtering

---
<h2><a class="anchor" id="health-problem"></a>Health Problem</h2>

Analysing early symptoms, Triggering causes and persisting health issues is crucial for prventing future health issues in patients. This Project aims to:

- Identifying gender specific impact
- Determine role of various trigger causes
- Analyze the medical history of patients
- Investigate relation between Age and Panic attack tendency


---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Used Snowflake as database source
- Summary table created from ingested data and used for analysis


---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- SQL (Basic Filtering & Cleaning)
- Power BI (DAX & Visualizations)
- GitHub


---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Removed transactions with:
  - Unique Patient ID = null

- Converted data types
- Grouped data into Age Group (Child, Adolescent, Adult/Senior)
- created new column Panic Category (Conditional column)


---

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Null Values in Unique Patient ID:**
- Deleted as it is unique and irreplacable


**Grouping Data using DAX function:**
- Grouped age into 3 Category
- Methods
    - If / Switch function
    - Conditional Column Method


---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>


1. **Number of Patients having Dizziness as a symptom**: 51% Patients 
2. **Average Panic Attack duration**: Mostly it remains for 24 minutes
3. **Impact of Caffeine intake**: Almost linear increase in number of panic attack with increase in caffeine dose.
4. **Exercise Frequency**: Patients with 0 ecercise frequency showed highest Panic score
5. **Age relation**:
   - Adult (24<>64): 85%
   - Adolescent (17<>24): 15%

---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Power BI Dashboard shows:
  - Number of Patients by symptoms (Dizziness, Trembling, Sweating, etc)
  
  - Slicer (Panic category, Gender, Trigger reason, Medical history)
  - Age Group Analysis
  


---


---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Abhishek Pathak**  
Data Analyst  
📧 Email: wayoflife507@gmail.com

    Contact No: +91 6307017308
    
🔗 [LinkedIn](https://www.linkedin.com/in/abhishekpathak2806/)  

