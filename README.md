# Electric Vehicle Market Segmentation in India

![EV Market](https://img.shields.io/badge/Focus-Market_Segmentation-blue)
![Python](https://img.shields.io/badge/Language-Python-green)
![License](https://img.shields.io/badge/License-MIT-orange)

## 📌 Overview
This project analyzes India’s electric vehicle (EV) market using **Telangana’s sales and registration data** (Oct-Nov 2023) to identify high-potential segments for startups. By leveraging **K-Means clustering** and **PCA**, it uncovers actionable insights into consumer preferences, market trends, and strategic opportunities in the EV sector.

## 🎯 Objectives
1. Identify the most promising EV segments (e.g., motorcycles, cars) for product development.
2. Analyze consumer behavior (e.g., insurance preferences, vehicle age).
3. Guide startups in prioritizing segments based on profitability and competition.

## 📂 Data Sources
- **Primary Data**: [Telangana Transportation Authority Portal](https://data.telangana.gov.in/search/?theme=Automobile)
  - Sales Data (Oct-Nov 2023): Model, fuel type, vehicle class, insurance validity.
  - Registration Data: Body type, engine capacity (CC), horsepower (HP).
- **Processed Dataset**: Combined and cleaned data with 8,691 entries and 14 variables.

## 🔍 Methodology
1. **Data Preprocessing**  
   - Merged sales and registration datasets.
   - Dropped irrelevant columns (`S.No`, `Company`, `Model`).
   - Encoded categorical variables (e.g., `Fuel`, `Vehicle Class`).

2. **Exploratory Data Analysis (EDA)**  
   - Visualized trends using bar charts and count plots.
   - Identified dominance of **battery-operated motorcycles** (81% market share).

3. **Segmentation**  
   - Applied **K-Means Clustering** (k=5) with PCA for 2D visualization.
   - Analyzed cluster characteristics (e.g., insurance validity, vehicle age).

4. **Insights & Recommendations**  
   - Prioritized **Segment 1 (motorcycles)** and **Segment 3 (motor cars)** for startups.

## 🚀 Key Findings
- **Market Leaders**: Battery-operated motorcycles dominate (81% share), led by **TVS Motors**, Ola, and Bajaj.
- **Consumer Preferences**:  
  - 99% of buyers prefer **5-year insurance** for motorcycles.  
  - 95% opt for **new EVs** (≤1 year old), with low demand for used vehicles.
- **Untapped Opportunities**: Hybrid and luxury EVs (e.g., Mercedes-Benz) remain underserved.
- **Technical Trends**: 98% of EVs have **0 engine capacity (CC)**, confirming the shift to battery tech.

## 🛠️ Tools Used
- **Python Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
- **Clustering**: K-Means, Elbow Method for optimal clusters.
- **Visualization**: PCA for 2D cluster plotting.
