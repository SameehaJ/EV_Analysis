# 🚗 Driving Change: Analyzing EV Adoption Trends Across the U.S.

## 📘 Background and Overview

This project presents a comprehensive Excel-based analysis of electric vehicle (EV) adoption trends in the U.S. using public data on EV registrations. The focus is on understanding how Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) are distributed geographically, how they differ in performance, and how CAFV (Clean Alternative Fuel Vehicle) eligibility affects adoption.

The dataset, sourced from Kaggle (https://www.kaggle.com/datasets/utkarshx27/electric-vehicle-population-data), includes over 114,000 records and was cleaned and analyzed using Power Query, Pivot Tables, Map Charts, and dynamic Excel formulas to build a multi-sheet interactive dashboard.

---

## 🎯 Project Requirements and Objectives

### Key Goals:
- Understand EV market size and growth across the U.S.
- Compare BEVs and PHEVs in terms of volume and range
- Analyze eligibility for CAFV incentives
- Identify high-adoption regions and leading brands
- Visualize trends with an engaging Excel dashboard

---

## 📊 Executive Summary

- BEVs represent over 76% of all EVs in the dataset
- Tesla leads in both registration count and electric range
- PHEVs commonly fall short of CAFV eligibility
- Washington State shows the highest EV adoption
- Policy, performance, and local incentives drive adoption diversity

---

## 🗃️ Data Structure Overview

### Dataset Columns (Raw):
- **VIN (1–10):** First 10 characters of vehicle ID  
- **Geography:** State, County, City, ZIP  
- **Vehicle Info:** Model Year, Make, Model, EV Type  
- **CAFV Eligibility:** Incentive eligibility flag  
- **Electric Range:** Max travel distance on battery  
- **Additional Fields:** MSRP, Legislative District, Utility, Coordinates

---

## 🧹 Data Cleaning (Power Query)

### Steps Taken:
- Used Power Query for step-by-step data prep
- Removed irrelevant columns (e.g., MSRP, Utility)
- Ensured clean, valid column types and structures
- Created a “Cleaned Data” sheet as the analysis base

---

## 📈 Analysis Walkthrough

### Sheet: **KPI**
- Total EVs, BEVs, PHEVs via Pivot Tables
- Pie charts show proportion breakdown
- `XLOOKUP`-powered tool to retrieve info by Vehicle ID

### Sheet: **State-wise**
- Pivot Table + Map Chart of EVs per U.S. state
- Highlights regional trends and adoption clusters

### Sheet: **Model Year**
- Chart of EV registrations by year
- Filters for focused analysis on post-2016 growth

### Sheet: **CAFV Eligibility**
- Segment vehicles by eligibility: Yes, No, Unknown
- Visualizes alignment with policy incentives

### Sheet: **Top 10 by Make**
- Registration count per manufacturer
- Top 10 filter applied via Pivot Chart

### Sheet: **Electric Range**
- Avg. electric range per brand
- Treemap visualization with slicers for model, year, type

### Sheet: **Dashboard**
- Interactive summary of KPIs + filters for:
  - EV Type
  - CAFV Status
  - Year
  - Make/Model

---

## 🔍 Key Insights

### 1. BEVs Dominate the EV Landscape
- 76.6% of vehicles are fully electric
- PHEVs are present but less dominant

### 2. Tesla’s Market Leadership
- 47,611 total registrations
- Leads in both CAFV eligibility and range

### 3. Range Determines Incentives
- Tesla: Avg. 243 km range  
- Many PHEVs fail to meet CAFV thresholds

### 4. Diverse Brand Strategies
- Some prioritize range; others focus on city driving
- Performance, incentives, and price shape adoption

### 5. State Policies Drive Growth
- Washington leads in adoption
- Local infrastructure and programs matter

---

## 💡 Recommendations

### For Policymakers:
- Clarify CAFV program details to buyers
- Reassess range criteria to include more PHEVs
- Address equity in how incentives are distributed

### For Automakers:
- Improve PHEV range to meet CAFV standards
- Report accurate range to ensure eligibility
- Build appeal beyond performance alone

### For Infrastructure Planners:
- Prioritize charging access in low-adoption zones
- Support both long- and short-range EVs
- Align plans with emerging adoption hotspots

---

## 🧾 Final Thoughts

This Excel-based project showcases how strong insights can be drawn from publicly available data — using nothing more than spreadsheets and storytelling. The structured approach from raw data to dashboard ensures transparency, reusability, and real-world relevance.
