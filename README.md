# Hospital-emergency-room-analytics

## 🚀 Project Overview

This project simulates a real-world healthcare scenario where the hospital's ER data is fragmented and poorly formatted. My goal was to build a reliable analytics solution that supports data-driven decisions by:

- Cleaning and transforming the raw dataset using SQL (SSMS)
- Performing Automated Data Exploration (ADE) in Python
- Creating an interactive Power BI dashboard
- Deploying everything in a GitHub repository for version control and visibility


A complete end-to-end data project where I clean, analyze, and visualize hospital emergency room data using **SQL**, **Python**, and **Power BI**. 

## 📊 Dashboard Preview

<img width="547" height="331" alt="image" src="https://github.com/user-attachments/assets/78c7b23f-8e41-4b08-9643-4926659b9772" />

---

## 🛠️ Tools Used

| Tool / Technology    | Purpose                                                                 |
|----------------------|-------------------------------------------------------------------------|
| 🗃️ **SQL (SSMS)**        | Cleaned and transformed raw ER data using SQL queries (`TRY_CONVERT`, `CASE`, `CAST`) |
| 🐍 **Python (Jupyter)**  | Used for Automated Data Exploration (ADE) and initial data profiling |
| 📚 **Pandas**            | Loaded and manipulated datasets, handled missing values and summaries |
| 🔢 **NumPy**             | Supported numeric computations and optimized data operations          |
| 📊 **Seaborn / Matplotlib** | Created plots like histograms, heatmaps, and boxplots for EDA         |
| 📈 **Power BI**          | Built an interactive dashboard to present insights visually           |
| 📁 **CSV**               | Data files used across SQL, Python, and Power BI                       |

This robust toolset enabled me to go from raw data to interactive business intelligence in a fully reproducible and modular workflow.


This stack allowed me to execute an end-to-end analytics workflow—from raw data to actionable business insights.






## 🧠 Business Objective

Hospital administrators want to understand ER performance. This includes:

- Which departments receive the most ER patients?
- How does patient wait time impact satisfaction?
- What age and gender demographics use ER services the most?
- Are there any operational inefficiencies in patient handling?

  


## 📁 Project Structure

├── 📂 data/
│ ├── Hospital_ER_Raw.csv # Original raw dataset
│ └── Hospital_ER_Cleaned.csv # Cleaned dataset exported after SQL transformation

├── 📂 sql scrip/
│ └── clean_hospital_er_data.sql # SQL script used for data cleaning in SSMS

├── 📂 notebook/
│ └── hospital_er_ade.ipynb # Python notebook for Automated Data Exploration (ADE)

├── 📂   Dashboard/
│ └── dashboard.pbix # Power BI dashboard file with interactive KPIs and visuals

├── 📄 README.md # Project documentation







---

## 🔍 Key Insights

- General Practice and Orthopedics are the most visited departments, indicating higher demand and potential staffing needs.
- Most patients wait under 60 minutes, but there are extreme cases with wait times over 200 minutes, suggesting periodic inefficiencies.
- Patient satisfaction is generally high when recorded, but over 65% of satisfaction scores are missing highlighting poor survey follow-up.
- A slight negative correlation exists between wait time and satisfaction, suggesting delays reduce patient happiness.
- Patients span a wide age range, with large representation in both pediatric and elderly groups important for care planning.
- Cleaned data now shows consistent formatting, valid types, and reduced nulls, making it ideal for analytics and visualization.

---



