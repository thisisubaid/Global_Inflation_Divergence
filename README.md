# Global Inflation Divergence: A Post-COVID Analysis

## Project Overview
This project analyzes why inflation recovery after COVID-19 (2020–2023) diverged sharply across countries. 
It examines how exchange rate stability and income levels influenced economic resilience, helping explain why some economies achieved a “soft landing” while others faced prolonged inflation shocks.

## Business Problem
Post-COVID inflation affected economies unevenly. Policymakers, investors, and businesses need to understand:
- Which countries recovered faster
- What economic factors contributed to resilience
- How future inflation risks can be anticipated

## Key Insights
- Turkey experienced inflation above 70%, while G7 economies averaged below 10%
- Exchange rate stability strongly correlated with faster inflation recovery
- The US and Germany achieved a “soft landing” (declining inflation with positive GDP growth)
- Emerging markets faced inflation shocks 3–5× larger than developed economies

## Methodology
- Cleaned and merged World Bank and IMF datasets using Python (pandas)
- Calculated post-COVID inflation shocks and recovery categories
- Analyzed relationships between inflation, GDP per capita, and exchange rate movements
- Built an interactive Tableau dashboard for cross-country comparison and storytelling

## Dashboard
🔗 **[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/mohammad.ubaidullah/viz/GlobalInflationDivergenceApostCOVIDAnalysis/Dashboard1)**

## Tools & Technologies
- Python (pandas) – data cleaning and exploratory analysis
- Tableau – interactive dashboards and storytelling
- Data Sources: World Bank (2005–2023), IMF

## Repository Structure
- `notebooks/inflation.ipynb` – Python EDA and preprocessing
- `data/processed/finall_countries_complete.csv` – Tableau-ready dataset
- `data/raw/` – Raw World Bank datasets (GDP, inflation, exchange rate)

## Limitations
- GDP growth used as a proxy for economic resilience
- Exchange rate impacts may vary by trade structure
- Analysis focuses on macro-level indicators, not household-level inflation

## 📁 Files Included
- `inflation.ipynb` - Complete Python analysis (data cleaning to visualization)
- `finall_countries_complete.csv` - Processed dataset ready for Tableau
- `gdp_per_capita.csv`, `inflaion_annual.csv`, `official_exchange.csv` - Raw data from World Bank
