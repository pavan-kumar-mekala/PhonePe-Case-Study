# PhonePe Case Study Analysis

## Overview
This repository contains a comprehensive analysis of PhonePe transaction and demographic data (2018–2021). The study focuses on usage trends, transaction behavior, device popularity, and actionable recommendations to optimize user engagement and growth.

## Objective
- Analyze state- and district-level transaction and user data.
- Identify trends in transaction volumes, types, and average values.
- Explore correlations with demographics, population, and device usage.
- Provide actionable insights for strategic decision-making.

## Data Sources
- `PhonePe.xlsx` – State-level and district-level transaction and user data.
- `districts.csv` – Unique mapping of district codes and names for consistency checks.

## Folder Structure
PhonePe_Case_Study/
├── notebook/
│   └── PhonePe.ipynb            # Jupyter/Colab notebook with full analysis
├── data/
│   ├── PhonePe.xlsx             # Raw Excel data from PhonePe
│   └── districts.csv            # District code-name mapping
├── images/                      # Optional: store charts, graphs, visualizations
│   └── example_chart.png
└── README.md                    # This README file

## Key Analysis Performed
- **Data Cleaning & Validation:** Missing value handling, data type checks, and consistency checks between state and district levels.
- **Exploratory Data Analysis (EDA):**  
  - Transaction trends over time  
  - Top/bottom states by transaction volume  
  - Popular transaction types and device brands  
  - Population distribution by district  
- **Advanced Analysis:**  
  - User-to-population ratio by state  
  - Average transaction per user  
  - Correlation of population density with transaction volume  
  - Device brand usage distribution

## Key Findings
- **Overall Growth:** Significant increase in transaction volumes and amounts from 2018–2021.  
- **Top States:** Karnataka, Maharashtra, and Telangana have the highest transaction volumes.  
- **Popular Transaction Types:** Merchant Payments and P2P transfers dominate.  
- **Device Usage:** Xiaomi is the most popular device brand in 35/36 states.  
- **High-Value Markets:** Telangana, Karnataka, and Andhra Pradesh have the highest average transaction per user.  
- **Low Adoption Areas:** Northeastern states generally have lower user-to-population ratios and transaction volumes.

## Recommendations
- **Target High-Growth Markets:** Focus on states with high transaction volumes and average transaction per user.  
- **Expand in Low-Penetration Areas:** Implement localized strategies to increase adoption in Northeastern states.  
- **Promote Financial Services:** Leverage high-ATV users for financial products.  
- **Optimize App Performance:** Ensure compatibility across popular devices like Xiaomi, Samsung, Vivo, and OnePlus.  
- **Monitor Transaction Types:** Continuously track trends to adapt marketing and product strategies.  
- **Use District-Level Data:** Implement targeted strategies based on local demographics and transaction patterns.

## Tools & Techniques
- **Excel:** Data cleaning, transformation, and visualization  
- **Jupyter Notebook (Colab):** Exploratory and advanced analysis  
- **CSV/XLSX:** Raw and processed datasets

## How to Explore
1. Clone the repository:
```bash
git clone https://github.com/pavan-kumar-mekala/PhonePe-Case-Study.git

2. Navigate to the notebook folder:
```bash
cd PhonePe-Case-Study/notebook

3. Open the `PhonePe.ipynb` notebook in **Colab** or **Jupyter Notebook** to explore the analysis step-by-step.

4. Explore the `data/` folder for raw and processed datasets (`PhonePe.xlsx` and `districts.csv`).

5. Optional: Check the `images/` folder for charts or visualizations referenced in the notebook or README.

## About
This project demonstrates analysis of PhonePe transactions and demographics in India (2018–2021). It provides actionable insights for business strategy, marketing, and user engagement.

