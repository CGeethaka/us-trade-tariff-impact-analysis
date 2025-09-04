# U.S. Trade & Tariff Impact Analysis – Power BI Dashboard

## Project Overview
This project analyzes the economic effects of U.S. tariffs in 2024, focusing on **trade deficits, tariff responses, and product-level price impacts**.  
The interactive dashboard was built with **Power BI**, integrating multiple datasets and applying **DAX measures** to generate meaningful insights.  

---

## Dashboard Preview
<img width="777" height="440" alt="Dashboard" src="https://github.com/user-attachments/assets/21f8ea3f-7ccc-43ee-8ca3-b4d120b2b09e" />



---

## Features & Methodology
- **Data Sources:**  
  - `Trump_Tariff_Data.xlsx` → Country-level trade data (exports, imports, tariffs, population)  
  - `Tariff.xlsx` → Time-series data (dates, countries, tariff status, GDP, inflation, etc.)  
  - *(Optional)* Additional product-level pricing data.  

- **Key DAX Measures Created:**  
  - **Net Trade** = Exports – Imports  
  - **Deficit per Capita** = Trade Deficit ÷ Population  
  - **Tariff Intensity %** = (Tariff-Imposed Trade ÷ Total Trade) × 100  
  - **Price Increase (%)** = (Price After Tariff – Price Before Tariff) ÷ Price Before Tariff  

- **Visuals Built:**  
  - **Map Charts** → Tariff intensity and trade deficit by country.
  - **Pie Chart** → Distribution of average effective tariff rate by goods targeted. 
  - **KPI Cards** → Net trade, deficit per capita, tariff intensity.  
  - **Area Charts** → Time-series of affected trade.  
  - **Tables** → Product-level price changes before vs. after tariffs.  
  - **Slicers & Tooltips** → Enhanced interactivity and storytelling.  

---

## Files in This Repository.
- `US_Trade_Tariff_Impact.pbix` → Main Power BI dashboard.  
- `Trump_Tariff_Data.xlsx` → Country-level dataset.  
- `Tariff.xlsx` → Time-series dataset.    
- `README.md` → Project documentation.  

---

## How to Use
1. Clone or download this repository.  
2. Open the `.pbix` file in **Power BI Desktop**.  
3. Use the provided datasets (`Trump_Tariff_Data.xlsx`, `Tariff.xlsx`) if re-importing or modifying the model.  
4. Explore the interactive visuals, slicers, and KPIs.  

---

## Insights
- Countries with high trade deficits are disproportionately affected by tariffs.  
- Tariff intensity varies across trade groups and directly impacts inflation indicators.  
- Product categor

