# A Comparative Climate Adaptation Study between Nigeria and the United States
This project is intended at comparing the impact of climate change on agricultural economies of Nigeria and the United States. 

## Objective
This project aims to: 
- **Identify the key factors driving economic losses related to climate impacts**
- **Determine which crops are most vulnerable to climatic changes.**
- **Evaluate the effectiveness of various climate adaptation strategies (e.g., water management, drought-resistant crops)**
- **Compare climate risks and adaptation outcomes between Nigeria and the United States.**
- **Assess whether successful adaptation strategies in one country (e.g., Nigeria) can be effectively transferred and applied in another context (e.g., the United States)**
---
## Methodology
### 1. **Data Source and Import**
The dataset used in this project contains climate and agricultural data of various countries. It was sourced from Kaggle and imported into Power Query from a locally stored Excel file.
  
### 2. **Data Preparation**  
Power Query was used to clean, preprocess, and transform the raw data for analysis.

**Data Filtering in Power Query:**

The dataset was refined to focus specifically on the two countries central to the study: **Nigeria** and **the United States**. Additional filtering was applied to retain only the columns relevant to the project objectives:
- Year
- Country
- Crop_Type
- Average_Temperature_C
- Crop_Yield_MT_per_HA
- Extreme_Weather_Events
- Adaptation_Strategies
- Economic_Impact_Million_USD

These selections ensured that the analysis remained aligned with the study’s comparative focus and allowed for clear insight into climate impacts, crop vulnerability, and adaptation strategies across both countries. 

<img src="assets/filteredcolumns.png" width="50%" />

### 3. **Data Analysis**  
DAX measures were created to support the analysis of crop performance, climate trends, and economic impacts across **Nigeria** and **the United States**. These measures calculate key metrics such as average crop yield, total economic losses, extreme weather event counts, and temperature insights. They form the foundation of the visualizations and enable meaningful comparisons between both countries. Refer to  [documentation/dax-measures.md](documentation/dax-measures.md) for a list of all measures. 
  
### 4. **Visualization:**
Interactive dashboards were built in Power BI to present findings clearly and effectively.

---

## Repository Structure
```
📁 Climate-Change-Impact-on-Agriculture/
│
├── 📄README.md
├── 📁 documentation/
│    ├── model-overview.md
|    ├── data-sources.md
|    └─  dax-measures.md 
├── 📁 pbix/
│    └─ report.pbix
└─  📁 assets/
     └─ (screenshots, diagrams)                     
```
---
