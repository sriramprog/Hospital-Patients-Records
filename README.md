## 🌟 Overview
This project showcases my skills in **data analytics**, **visualization**, and **data storytelling** using **Python** and **Power BI**. The goal was to process, clean, and analyze synthetic hospital datasets (2011-2022, Massachusetts) and present actionable insights through interactive dashboards.

## 🎯 Objective
To analyze patient records and build a dashboard for hospital stakeholders, highlighting trends, KPIs, and metrics of interest.

## 📊 Data Description
The project uses five datasets:

1. **Encounters**: Purpose of each patient visit (e.g., in-patient, outpatient, surgery, etc.).
2. **Patients**: Biographical details, such as name, address, marital status, and ethnicity.
3. **Procedures**: Medical procedures provided (e.g., MRI, depression screening).
4. **Organizations**: High-level hospital information (used minimally).
5. **Payers**: Major U.S. health insurance providers (used minimally).

## 🛠️ Tools & Techniques
- **Python**: Data cleaning, exploratory data analysis
- **Power BI**: Dashboard creation
- **DAX Functions**: Relationships, calculated fields

## 💡 Key Highlights

### Data Cleaning:
1. Standardized names using **regex** and fixed 4-digit zip codes with Python **lambda** functions.
2. Created calculated fields like **Age** (difference between DOB and current date) and **Full Name** (concatenation).

### Imputation & Transformation:
1. Imputed missing procedure codes with 'unknown' or '0'.
2. Calculated **Duration** of medical procedures using start/stop times.

### Insight Generation:
1. Classified admissions as **First-Time** or **Readmissions** with flag columns.
2. Analyzed **average stay duration** and **insurance costs** by encounter type.
3. Merged data to identify procedures covered by insurance, categorized by provider.

### Power BI Dashboards:
1. Built relationships across tables using shared keys.
2. Created **Age Categories** using **DAX nested IF statements**.
3. Developed visuals for readmission trends, procedure costs, and insurance breakdowns.

## 🌟 Challenges & Solutions

### Understanding Domain-Specific Data:
Initially, distinguishing between **Encounters** and **Procedures** was challenging. Research clarified their unique roles in hospital analytics, improving analysis depth.

### Integrating Data:
Combining tables like **Procedures** and **Encounters** required SQL-like joins in Python, involving key identification and thoughtful merging.

### Prioritizing KPIs:
Choosing metrics required stakeholder perspective, focusing on insights that truly matter.

## 📈 Results
- Visualized patient trends and billing metrics
- Provided actionable insights for stakeholders
- Delivered a dashboard demonstrating clean data and impactful visual storytelling

## 📸 Visuals
Static screenshots of Power BI dashboard are included in this repository.

## 🔗 Repository Contents
- **`Hospital Patient Records.py`**: Python script for data preprocessing and analysis
- **`Hospital Dashboard.png`**: Power BI dashboard (static screenshots)

## 🚀 Next Steps
- Explore predictive modeling using this dataset
- Enhance dashboards with user-interactive features
