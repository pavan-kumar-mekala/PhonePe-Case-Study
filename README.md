# PhonePe Digital Transactions Analysis

## Overview  
This project presents a comprehensive analysis of PhonePe’s transaction, user, device, and demographic data (2018–2021). The objective is to identify digital adoption trends, regional transaction behavior, and usage patterns using Python (Google Colab) and Power BI.

---

## Objectives  

- Analyze state- and district-level transaction and user data  
- Identify trends in transaction volumes, transaction types, and average values  
- Explore correlations with population, demographics, and device usage  
- Derive insights and propose data-driven recommendations  

---

## Data Sources  

- **PhonePe.xlsx** – State-level and district-level transaction and user data  
- **districts.csv** – Unique district code mapping for validation and aggregation checks  

---

## Key Analysis Performed  

### Data Cleaning & Validation  
- Handled missing values and incorrect records  
- Validated data types and schema consistency  
- Performed consistency checks between state-level and district-level aggregates  

### Exploratory Data Analysis (EDA)  
- Transaction growth trends (2018–2021)  
- Top and bottom states by transaction volume  
- Popular transaction types and device brands  
- District-level population distribution  

### Advanced Analysis  
- User-to-population ratio by state  
- Average transaction value per user  
- Correlation (~0.31) between population density and transaction volume  
- Device brand usage distribution across states  

Gemini AI was used to validate hypotheses and assist in summarizing complex analytical patterns.

---

## Key Findings  

- Significant increase in transaction volumes and value between 2018–2021  
- Karnataka, Maharashtra, and Telangana lead in transaction volume  
- Merchant Payments and P2P transfers dominate transaction types  
- Xiaomi is the leading device brand in 35 of 36 states  
- Telangana, Karnataka, and Andhra Pradesh show the highest average transaction value per user  
- Northeastern states show lower user-to-population ratios and transaction volumes  

---

## Recommendations  

- Focus growth strategies on high-volume, high-ATV states  
- Develop localized initiatives to improve adoption in low-penetration regions  
- Explore cross-selling financial products in high-ATV segments  
- Optimize app performance for dominant device ecosystems  
- Leverage district-level insights for hyper-local targeting  

---

## Power BI Dashboard  

An interactive 3-page dashboard was developed to present insights:

1. Executive Overview – KPIs and Top States  
2. State Performance Analysis – Transactions, value, users  
3. Device & Transaction Insights – Device share, transaction types, ATV  

### Technical Highlights  

- Star schema modeling (Dim_State, Dim_District, Dim_Date)  
- DAX measures for KPI calculations  
- Synced slicers and dynamic Top-N filtering  

---

## Tools & Technologies  

- Python (Google Colab): pandas, numpy, matplotlib  
- Power BI: Data modeling, DAX measures, interactive dashboards  
- Gemini AI: Hypothesis validation and analytical summarization  
- Excel / CSV / XLSX: Source datasets  

---

## How to Explore  

Clone the repository:

```bash
git clone https://github.com/pavan-kumar-mekala/PhonePe-Case-Study.git
```
