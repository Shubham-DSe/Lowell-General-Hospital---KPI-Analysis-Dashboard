# Lowell-General-Hospital---KPI-Analysis-Dashboard**End-to-End Data Analysis Project**  
**Analyzing the relationship between Bed Occupancy, Staff Responsiveness, and Patient Safety (Unassisted Falls)**

---

### 📋 Project Overview
This project analyzes 60 months of operational data from Lowell General Hospital to understand how **bed occupancy rate** impacts **staff responsiveness** and **unassisted patient fall rates**.  

The goal was to identify key correlations, build interactive visualizations, and provide practical recommendations to improve patient safety and operational efficiency.

---

### 🎯 Problem Statement
High bed occupancy often leads to increased pressure on hospital staff, resulting in lower responsiveness and higher unassisted fall incidents. The hospital wanted to:
- Quantify the relationship between the three KPIs
- Identify trends and patterns over time
- Compare performance against benchmarks
- Provide data-driven recommendations for staffing and training

---

### 📊 Dataset
- **Time Period**: 60 months (Jan 2020 – Dec 2024)
- **Key Variables**:
  - Average Licensed Bed Occupancy Rate
  - Staff Responsiveness Domain Top Box Score (HCAHPS)
  - Unassisted Fall Rate per 1,000 Patient Days
- **Source**: Hospital internal records (anonymized)

---

### 🛠️ Tools & Technologies
- **Python**: Pandas, NumPy, SciPy, Matplotlib, Seaborn
- **Power BI**: Interactive Dashboard with KPI cards and trend charts
- **Analysis**: Correlation Analysis (Pearson), Data Cleaning, Trend Analysis

---

### 🔍 Key Analysis & Insights
- Calculated Pearson correlations:
  - **Occupancy Rate vs Fall Rate**: **+0.70** (Strong Positive)
  - **Occupancy Rate vs Staff Responsiveness**: **-0.37** (Moderate Negative)
  - **Fall Rate vs Staff Responsiveness**: **-0.79** (Strong Negative)
- Staff responsiveness consistently remained below the benchmark of 65 in most months.
- Higher occupancy periods showed increased fall rates and reduced staff responsiveness.

---

### 📈 Visualizations & Dashboard
- Monthly trend analysis of all three KPIs
- Correlation heatmap
- Scatter plots with regression lines
- Interactive **Power BI Dashboard** with:
  - KPI cards with benchmark comparison
  - Monthly trend charts
  - Year-wise filtering

---

### 💡 Recommendations
- Maintain optimal staff-to-patient ratio during high occupancy periods (>95%)
- Implement targeted staff responsiveness training during peak occupancy months
- Introduce real-time monitoring of call-button response time
- Consider increasing nursing staff by 8–10% during high occupancy to reduce fall incidents

---

### 📁 Repository Contents
- `Lowell_KPI_Analysis.ipynb` → Complete Python analysis and visualizations
- `Cleaned_Data_for_PowerBI.xlsx` → Cleaned dataset ready for dashboard
- `KPI_Dashboard.pbix` → Power BI dashboard file
- `Trends.png`, `Correlation_Heatmap.png`, `Scatter_*.png` → Generated charts
- `Lowell_General_Hospital_KPI_Presentation.pptx` → Final presentation

---

### 🚀 How to Run the Project
1. Clone the repository
2. Open `Lowell_KPI_Analysis.ipynb` in Jupyter Notebook
3. Run all cells (requires pandas, numpy, matplotlib, seaborn, scipy)
4. Open `KPI_Dashboard.pbix` in Power BI Desktop to view the interactive dashboard

---

### 👤 Author
**Shubham Waghade**  
Data Analyst | B.Tech (Electronics & Communication)  
[LinkedIn](https://linkedin.com/in/shubham-waghade-26a9a0237) | [GitHub](https://github.com/Shubham-DSe)

---
