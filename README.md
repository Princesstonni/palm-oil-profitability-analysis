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
6. [Skills Demonstrated](#-skills-demonstrated)  
7. [Author](#-author)  
8. [License](#-license)

---

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

### *3. Adjusted Yield Formula*
Adjusted_Yield = Base_Yield * Scenario_Multiplier

### *4. State-Level Financial Modeling*
For each state and each year:
- Adjusted production  
- Adjusted costs  
- Adjusted revenue  
- Profit per hectare  
- Required land area to achieve ₦1B profit  

---

## 📈 Key Insights

### ⭐ Edo State is the most profitable  
Strongest yield performance + operational efficiency.

### ⭐ Average Base Scenario Profit per ha

