# London vs Sydney: Data Analyst Market Analysis

> A data-driven comparison of salary, rent, and quality of life for Data Analysts in two global cities

## 📌 Overview  

This project analyzes the affordability and quality of life for **Data Analysts** across experience levels in **London** and **Sydney**.

Rather than comparing gross salaries, I calculated **real disposable income** after taxes, rent, and essential living costs to answer a personal question:

> **Where should I start my Data Analytics career?**

**Key Question:** Which city lets Data Analysts save more money while maintaining quality of life?

**Spoiler:** The answer changes based on your experience level.

## 🎯 Objectives  

- Compare after-tax Data Analyst salaries  
- Analyze rental affordability by suburb  
- Estimate disposable income after fixed costs  
- Visualize differences across experience levels  

---

## 🗂 Data Sources  

- Glassdoor – Data Analyst salary ranges  
- NSW Rental Bond Data – Sydney rent by suburb  
- UK Office for National Statistics – London rent data  
- Cost of Living datasets – utilities, food, transport  


---

## 🛠 Tech Stack  

- SQL  
- Excel  
- Tableau  

**Note:** This project deliberately used Excel + SQL to demonstrate core data analysis skills without over-engineering.

---

## 🔄 Pipeline  

1. Data scraping & ingestion  
2. Cleaning and normalization  
3. SQL aggregation and transformations  
4. Metric creation (after-tax income, rent, disposable income)  
5. Visualization in Tableau  

---

## 📊 Key Metrics  

| Metric | Description | Formula |
|--------|-------------|---------|
| **After-Tax Income** | Monthly take-home by experience level | `(Annual Salary - Tax) / 12` |
| **Monthly Rent** | Average 1-bedroom by suburb | `Weekly Rent × (52/12)` |
| **Basic Living Costs** | Food, transport, utilities, phone, healthcare | Sum of monthly essentials |
| **Disposable Income** | Money left for savings/lifestyle | `Take Home - Rent - Basic Costs` |
| **Affordability Tier** | Risk assessment by suburb | Comfortable / Manageable / Tight / Risky |
| **3-Year Savings** | Potential accumulated savings | `(Disposable × 0.35) × 36 months` |

**Assumptions:**
- 1-bedroom apartment (solo living)
- Minimum salary scenario (conservative approach)
- 35% savings rate (moderate scenario)
- Fixed exchange rate for consistency

---

## 📁 Project Structure  
/data -> raw and cleaned datasets
/sql -> SQL queries
/dashboards -> Tableau files / exports
/figures -> charts and visuals
README.md


---

## ▶ How to Run  

1. Clone the repository  
2. Load datasets from `/data`  
3. Execute SQL scripts from `/sql`  
4. Open Tableau dashboard from `/visuals`  

---

## 🔍 Results Summary  

- Sydney provides stronger junior purchasing power.  
- London becomes competitive at higher experience levels.  
- Renting alone is risky early-career in both cities.  
- Outer suburbs offer the best affordability.  

---

## 📖 About This Project

This analysis was created as my **Data Analytics Accelerator Capstone Project**.

### Why This Topic?

I spent the last months of 2025 in Sydney and fell in love with it. But I'd always dreamed of living in London. Facing a career pivot from cultural heritage (archaeology/conservation) to data analytics, I needed to make an informed decision.

Instead of guessing, I built a complete data pipeline to analyze where I could build a better career foundation.

### What I Learned

- Real-world data is messy (90% cleaning, 10% analysis)
- Personal stakes improve data quality (when it matters, you don't cut corners)
- SQL is powerful for filtering complex scenarios
- Interactive visualizations let others apply your insights to their situations

### Skills Demonstrated

- **Data Collection**: Multi-source scraping and aggregation
- **Data Cleaning**: Excel formula wizardry across 800+ records
- **Data Analysis**: SQL queries for complex filtering
- **Visualization**: Interactive Tableau dashboards
- **Problem Solving**: Real-world decision-making under uncertainty
---

## 📬 Contact  
**Open to opportunities in:** Data Analytics, Database Development, Remote positions (EU-based)

Created by Harris Georgakis
LinkedIn: https://www.linkedin.com/in/harrisgeorgakis/ 


