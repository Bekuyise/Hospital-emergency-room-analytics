# Hospital-emergency-room-analytics

## 🎯 Project Objective

To build a real-time Azure-based data pipeline that ingests, transforms, and analyzes hospital data, ensuring reliable patient care analytics and operational efficiency. The solution leverages Azure Data Factory, Azure Databricks, Event Hub, Azure SQL Database, Power BI, and Key Vault for secure credential management.


###  🛠️ Tools Used

| Tool / Technology    | Purpose                                                                 |
|----------------------|-------------------------------------------------------------------------|
| 🗃️ **SQL (SSMS)**        | Cleaned and transformed raw ER data using SQL queries (`TRY_CONVERT`, `CASE`, `CAST`) |
| 🐍 **Python (Jupyter)**  | Used for Automated Data Exploration (ADE) and initial data profiling |
| 📚 **Pandas**            | Loaded and manipulated datasets, handled missing values and summaries |
| 🔢 **NumPy**             | Supported numeric computations and optimized data operations          |
| 📊 **Seaborn / Matplotlib** | Created plots like histograms, heatmaps, and boxplots for EDA         |
| 📈 **Power BI**          | Built an interactive dashboard to present insights visually           |
| 📁 **CSV**               | Data files used across SQL, Python, and Power BI                       |




# 📊 Dashboard Preview

<img width="547" height="331" alt="image" src="https://github.com/user-attachments/assets/78c7b23f-8e41-4b08-9643-4926659b9772" />

# 📊 Power BI Dashboard
🧑‍⚕️ Patient Distribution by Department 
⏳ Patient Wait Time Analysis 
👥 Demographic Insights
📅 Appointment Trends 
📈 Satisfaction Correlation 


# 🔍 Key Insights

- General Practice and Orthopedics are the most visited departments, indicating higher demand and potential staffing needs.
- Most patients wait under 60 minutes, but there are extreme cases with wait times over 200 minutes, suggesting periodic inefficiencies.
- Patient satisfaction is generally high when recorded, but over 65% of satisfaction scores are missing highlighting poor survey follow-up.
- A slight negative correlation exists between wait time and satisfaction, suggesting delays reduce patient happiness.
- Patients span a wide age range, with large representation in both pediatric and elderly groups important for care planning.
- Cleaned data now shows consistent formatting, valid types, and reduced nulls, making it ideal for analytics and visualization.


# 📈 Business Impact

### This  solution empowers the hospital to:

Enhance patient service delivery through real-time data insights

Reduce reporting lag by eliminating manual processes

Track and optimize treatment effectiveness and patient wait times

























































