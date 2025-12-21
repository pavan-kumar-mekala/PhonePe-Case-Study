#  PhonePe Case Study Analysis

##  Overview
This project presents a comprehensive, **AI-assisted analysis** of PhonePe’s transaction, user, device, and demographic data from **2018 to 2021**.  
The objective is to uncover usage trends, digital adoption patterns, and regional behavior, and to translate insights into **actionable business recommendations** using **Python (Google Colab), Gemini AI, and Power BI**.

---

##  Objectives
- Analyze state- and district-level transaction and user data  
- Identify trends in transaction volumes, transaction types, and average values  
- Explore correlations with demographics, population, and device usage  
- Provide actionable insights for strategic decision-making  

---

##  Data Sources
- **PhonePe.xlsx** – State-level and district-level transaction and user data  
- **districts.csv** – Unique mapping of district codes and district names for consistency checks  

---

##  Key Analysis Performed

###  Data Cleaning & Validation
- Handled missing values and incorrect records  
- Performed data type validation  
- Conducted consistency checks between state-level and district-level aggregates  

###  Exploratory Data Analysis (EDA)
- Transaction trends over time (2018–2021)  
- Top and bottom states by transaction volume  
- Popular transaction types and device brands  
- Population distribution by district  

###  Advanced & AI-Assisted Analysis
- User-to-population ratio by state  
- Average transaction value per user  
- Correlation between population density and transaction volume  
- Device brand usage distribution  
- **Gemini AI** used for hypothesis validation and summarizing complex patterns  

---

##  Key Findings
- **Overall Growth:** Significant increase in transaction volumes and amounts from 2018–2021  
- **Top States:** Karnataka, Maharashtra, and Telangana lead in transaction volume  
- **Popular Transaction Types:** Merchant Payments and P2P transfers dominate usage  
- **Device Usage:** Xiaomi is the most popular device brand in **35 out of 36 states**  
- **High-Value Markets:** Telangana, Karnataka, and Andhra Pradesh show the highest average transaction per user  
- **Low Adoption Areas:** Northeastern states have lower user-to-population ratios and transaction volumes  

---

##  Recommendations
- **Target High-Growth Markets:** Focus on states with high transaction volumes and high average transaction per user  
- **Expand in Low-Penetration Areas:** Implement localized strategies to increase adoption in Northeastern states  
- **Promote Financial Services:** Leverage high-ATV users for cross-selling financial products  
- **Optimize App Performance:** Ensure compatibility across popular devices (Xiaomi, Samsung, Vivo, OnePlus)  
- **Monitor Transaction Types:** Continuously track trends to refine product and marketing strategies  
- **Leverage District-Level Data:** Apply hyper-local strategies using demographic and transaction insights  

---

##  Power BI Dashboard
An interactive **3-page Power BI dashboard** was built to present insights clearly:
- **Executive Overview:** KPIs, trends, Top 10 states  
- **State Performance Analysis:** State-wise transactions, amount, and users  
- **Device & Transaction Insights:** Transaction types, device usage, ATV metrics  

**Technical highlights:**
- Star schema modeling (Dim_State, Dim_District, Dim_Date)  
- DAX measures for KPIs  
- Synced slicers and Top-N filtering  

---

##  Tools & Technologies
- **Python (Google Colab):** pandas, numpy, matplotlib, seaborn  
- **Gemini AI:** AI-assisted insight validation and pattern analysis  
- **Power BI:** Data modeling, DAX measures, interactive dashboards  
- **Excel / CSV / XLSX:** Source and processed datasets  

---

##  How to Explore

Clone the repository:
```bash
git clone https://github.com/pavan-kumar-mekala/PhonePe-Case-Study.git
