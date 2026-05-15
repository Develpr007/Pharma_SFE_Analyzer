Pharma Sales Force Effectiveness (SFE) AnalyzerAn End-to-End Decision Analytics Project: Addressing ROI Decline through Predictive Modeling & Resource Optimization

📌 Project Overview
This project simulates a real-world consulting engagement for a pharmaceutical client facing a critical ROI challenge: Operational costs increased by 12%, while market share grew by only 3%.
I developed a multi-stage analytical pipeline to diagnose the root causes of this inefficiency, identify wasted field force effort, and build a predictive early-warning system for representative performance.

🚀 Impact & Results
->Revenue Opportunity: Identified a ₹3.2 Crore incremental revenue gain through precision targeting of uncalled high-value prescribers.
->Efficiency Gains: Pinpointed a "Call Plateau" at 12 visits/month, revealing that 20% of field effort was spent on diminishing returns.
->Predictive Accuracy: Developed a Random Forest model to predict "At-Risk" representatives based on behavioral DNA (A-Tier reach rate, tenure, and MPI).
->Strategic Roadmap: Delivered a 90-day implementation plan to reallocate 15% of the field force from low-potential to high-potential territories. 

🛠️ Tech Stack & Methodology1. 
1. Data Engineering & SQLETL:
   ->Cleaned 50,000+ records of "messy" sales, call, and prescriber data using Python.
   ->Star Schema: Developed a robust SQL database architecture (Dimensions/Facts) for high-performance reporting.
   ->Advanced SQL: Utilized Window Functions (LAG, PERCENT_RANK) and Complex Joins to calculate longitudinal MoM growth and peer rankings.

2. Machine Learning (Predictive Analytics)
   ->Problem: Identify reps likely to miss target achievement thresholds (<85%).
   ->Model: Random Forest Classifier.
   ->Key Finding: Feature importance analysis revealed that A-Tier Reach Rate is a 2.3x stronger predictor of success than raw call volume.
  
4. Business Intelligence (Power BI)
   Built a 4-page executive-grade interactive dashboard:
   ->Executive Summary: High-level KPIs and workforce health donut charts.
   ->Territory Intelligence: A dynamic BCG Matrix (Market Potential vs. Achievement).
   ->Deep Dive: Call frequency correlation analysis and targeting audits.
   ->Actionable Lists: The "Quick Wins" table identifying uncalled A-tier doctors.

💡 Key Business InsightsThe 
    ->12-Call Rule: Beyond 12 calls per month to a single prescriber, the incremental gain in brand share drops by 85%. This indicates significant "over-servicing" of current accounts at the expense of new targets.
    ->Targeting Mismatch: 32% of the workforce are currently assigned to "Dog" territories (low potential), suggesting a massive need for geographic reallocation.
    ->The Shocking Gap: 40% of the most valuable (A-Tier) prescribers were visited less than once per quarter.

🏗️ Repository Structure
pharma-sfe-analyzer/
│
├── 1. Thinking Phase/
│   └── Phase_1_Thinking.pdf
│
├── 2. Raw data/
│   ├── calls.xlsx
│   ├── prescribers.xlsx
│   ├── reps.xlsx
│   ├── sales.xlsx
│   ├── territories.xlsx
│   └── pharma_sfe.db
│
├── 3. Processed Data/
│   ├── calls_fact.xlsx
│   ├── prescribers_dim.xlsx
│   ├── reps_dim.xlsx
│   ├── sales_fact.xlsx
│   ├── territories_dim.xlsx
│   └── processed_pharma_sfe.db
│
├── 4. Notebooks/
│   ├── 01_data_generation.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda_analysis.ipynb
│   ├── 04_segmentation.ipynb
│   ├── 05_statistical_tests.ipynb
│   └── 06_ml_model.ipynb
│
├── 5. SQL Queries/
│   ├── analysis_queries.sql
│   └── SQL_Queries.pdf
│
├── 6. Power BI/
│   ├── Dashboard.pbix
│   ├── Dashboard Images/
│   └── Power_BI_Data/
│
├── 7. Consulting Report & Deck/
│   ├── Executive_Pharma_SFE_Report.pdf
│   └── Executive_Pharma_SFE_Deck.pdf
│
└── README.md
    
👨‍💻 How to RunEnvironment: 
   ->Ensure you have Python 3.10+, Pandas, Scikit-learn, and SQLite3 installed.
   ->Pipeline: Run the notebooks in sequential order (01 $\rightarrow$ 02 $\rightarrow$ 03).
   ->Visualization: Open the .pbix file in Power BI Desktop to explore the live dashboard.
   ->Strategy: Read the executive_strategy_report.pdf for the final business recommendations.
   
Contact:-
Abhijeet Singh | www.linkedin.com/in/abhijeet-singh-bit | abhijeet3232348@gmail.com
