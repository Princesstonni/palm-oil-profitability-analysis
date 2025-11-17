# 🌴 Palm Oil Profitability Analysis (2019–2025)  
### A Data-Driven Financial Model for Edo, Ondo & Cross River Built From Scratch

This project presents a complete profitability model for Nigeria’s palm oil sector across Edo, Ondo, and Cross River States, covering the years 2019–2025.  
No dataset was provided all data was manually collected, cleaned, and modeled from FAOSTAT and Okomu Oil PLC.

The goal of this analysis is to estimate:
- Profit per hectare  
- Cost and revenue dynamics  
- Operational efficiency  
- Break-even point  
- Land size required to achieve *₦1,000,000,000 annual profit*

---

## 📚 Table of Contents  
1. [Project Summary](#-project-summary)  
2. [Methodology](#-methodology)  
   - [Data Cleaning & Structuring](#1-data-cleaning--structuring)  
   - [Scenario Modeling](#2-scenario-modeling)  
   - [Adjusted Yield Formula](#3-adjusted-yield-formula)  
   - [State-Level Financial Modeling](#4-state-level-financial-modeling)  
3. [Key Insights](#-key-insights)  
4. [Dashboard (Power BI)](#-dashboard-power-bi)  
5. [Repository Structure](#-repository-structure)
6. [How to Use This Project](#-how-to-use-this-project)
7. [Skills Demonstrated](#-skills-demonstrated)  

---

## Prepared by: Osolake Mariam Omotolani


## 📌 Project Summary

Because state-level datasets do not exist publicly, I built this model *from the ground up* using:

### *1️⃣ National Data from FAOSTAT*
- Production (tonnes)  
- Harvested area (ha)  
- Yield  
- Global and regional price data  

### *2️⃣ Company-Level Benchmarks from Okomu Oil PLC*
- Revenue  
- Cost of sales  
- Profit before tax  
- Realistic production efficiency  

The national dataset was then proportionally allocated to the three states using:

- *Edo — 40%*  
- *Ondo — 35%*  
- *Cross River — 25%*

---

## 🔧 Methodology

### *1. Data Cleaning & Structuring*
- Extracted raw values from PDF reports  
- Converted all units to consistent formats (tonnes, hectares, naira)  
- Fixed missing values and cleaned inconsistencies  
- Standardized the dataset for the years 2019–2025  

### *2. Scenario Modeling*
Three forecast scenarios:

| Scenario | Yield Multiplier | Cost Impact | Revenue Impact |
|---------|------------------|-------------|----------------|
| *Conservative* | 0.85 | Higher costs | Lower revenue |
| *Base* | 1.00 | Standard | Standard |
| *Optimistic* | 1.10 | Lower costs | Higher revenue |

### *3. Adjusted Yield Formula:*
Adjusted_Yield = Base_Yield * Scenario_Multiplier
Applied scenario multipliers to model realistic outcomes

### *4. State-Level Financial Modeling*
For each state and each year:
- Adjusted production  
- Adjusted costs  
- Adjusted revenue  
- Profit per hectare  
- Required land area to achieve ₦1B profit

  ### *5. Profit Cpmputation:*
  Profit per ha = Revenue per ha - Cost per ha

  ### *6. Break-even Estimation:*
  Determine hectares to required to hit a 1B naira profit target

---

## 📈 Key Insights

### ⭐ Edo State is the most profitable  
Strongest yield performance + operational efficiency.

### ⭐ Average Base Scenario Profit per ha
₦801,000 per hectare

### ⭐ Land Required to Hit ₦1B Profit: ≈ 109 hectares
### ⭐ Cross River has the lowest margins  
Due to higher operating costs.

### ⭐ Optimistic scenario demonstrates strong potential  
Higher efficiency → significantly higher profit margins.

---

## 📊 Dashboard (Power BI)

Visualizations include:
- Profitability comparison across states  
- Yield vs profit correlation  
- Revenue vs cost trends  
- Scenario-based financial outcomes  
- Required area for ₦1B profit

  *Interactive Power BI Dashboard:*  
https://app.powerbi.com/view?r=eyJrIjoiYWIxODBkZTMtOGZhNS00YzE0LTk4MDItNWExYjBhYjlkNTFiIiwidCI6ImMyYjE1OGJkLTZkMTItNDQzZC1iYTUwLTM1NTUzYjE4N2UyNSJ9

## 📁 Repository Structure

├── Data_Sources_List.xlsx               # Documentation of all sources used
├── FAOSTAT_PalmOil_Data.csv             # Cleaned palm oil production data
├── Okomu_report_data.xlsx               # Extracted benchmark data from Okomu annual reports
├── PalmOil_Profitability_Model_Clean.xlsx # Final cleaned modeling workbook (yields, costs, scenarios)
├── PalmOil_Profitability_Dashboard.pbix # Power BI dashboard file
├── PalmOil_Profitability_Report.pdf     # Final analyst report (executive summary + insights)
├── palmoil dashboard.png                # Dashboard screenshot for README
├── README.md                            # Project overview, insights & instructions

## 🚀 How to Use This Project
1. *Clone the Repository*
   ```bash
   git clone https://github.com/Princesstonni/palm-oil-profitability-analysis.git
or download the ZIP file directly from GitHub.

 2.	*Open the Dataset*
	•	Navigate to the Excel files:
	•	FAOSTAT_PalmOil_Data.csv
	•	Okomu_report_data.xlsx
	•	PalmOil_Profitability_Model_Clean.xlsx
	•	These contain raw data, cleaned data, and the final profitability model.

	3.	*Explore the Profitability Model*
	•	Open PalmOil_Profitability_Model_Clean.xlsx.
	•	Review:
	•	Yield per hectare calculations
	•	Cost & revenue modeling
	•	Conservative, Base & Optimistic scenario adjustments
	•	State-level comparisons (Edo, Ondo, Cross River)
	•	₦1 billion profit break-even analysis

	4.	*Run the Interactive Dashboard*
	•	Download the PalmOil_Profitability_Dashboard.pbix file.
	•	Open it in Power BI Desktop.
	•	You can:
	•	Filter by state
	•	Compare yearly performance (2019–2025)
	•	View cost vs revenue trends
	•	Analyze profitability per hectare
	•	See required area to reach ₦1B annual profit

	5.	*View the Published Dashboard Online*
	•	Click the live version link (above in README)
View Interactive Dashboard
   •	No installation required.

	6.	Read the Final Report
	•	Open PalmOil_Profitability_Report.pdf to understand:
	•	Key insights
	•	Investment recommendations
	•	Scenario conclusions
	•	Data assumptions and limitations

	7.	Use this Project for Learning or Re-Analysis
	•	You can reuse the modeling framework for:
	•	Agricultural profitability analysis
	•	State-level or farm-level investment simulations
	•	Sensitivity & scenario forecasting
	•	Yield and cost optimization studies

## Skills Demonstrated

- *Data Sourcing & Web Research*  
  Extracted production, yield, cost, and financial benchmark data from FAOSTAT and Okomu Oil PLC reports.

- *Data Cleaning & Transformation (Excel)*  
  Standardized units, handled missing values, calculated adjusted yields, built scenario models (Conservative, Base, Optimistic).

- *Analytical Modeling*  
  Developed per-hectare profitability metrics, revenue/cost models, and ₦1B profit break-even simulations across three states.

- *Scenario Analysis*  
  Applied percentage adjustments to yields and costs; evaluated sensitivity across state and year variations (2019–2025).

- *Data Visualization (Power BI)*  
  Designed an interactive dashboard showcasing profitability insights, trends, and investment recommendations.

- *Business Insight & Reporting*  
  Produced a professional PDF report summarizing financial implications, state ranking, and strategic recommendations.

- *Version Control & Documentation*  
  Organized datasets, models, visualizations, and reports into a structured GitHub repository with detailed README documentation.

