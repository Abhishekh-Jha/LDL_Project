LDL Cholesterol Awareness Analysis (NHANES 2017–2018)

Data Analysis |  Statistical Modeling |  Power BI Dashboard

 Overview
This project analyzes LDL cholesterol awareness among US adults using the NHANES 2017–2018 dataset.  
The objective is to identify awareness gaps across age, ethnicity, and gender and present insights through python analysis, SQL queries, and an interactive Power BI dashboard.

Dataset
- Source: [NHANES 2017–2018](https://wwwn.cdc.gov/nchs/nhanes/)  
- Modules used: Demographics, Lipid Profile (HDL, LDL, Triglycerides, Total Cholesterol), and Health Questionnaire  
- Participants: ~9,000 individuals  

 Tools & Technologies
- Python: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels  
- SQL: Data extraction & querying  
- Power BI: Interactive dashboards & storytelling  
- GitHub: Version control & documentation  

  Workflow
1. Data cleaning & preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Statistical tests (Logistic Regression)  
4. Clustering to segment participants  
5. Visualization & dashboarding in Power BI  

 Key Insights
- Awareness lowest among young adults (18–30 years)
- Ethnic disparities observed (lower awareness in Mexican Americans)  
- No significant gender gap found  
- Action Plan: Targeted youth campaigns & community-based screening

Action plan
- Youth awareness campaigns (digital/social health campaigns).
- Targeted screening in Mexican American Communities.
- Reinforce communication for high-Risk (LDL>130 mg/dL) groups.
  
 Dashboard
![Dashboard Preview](https://github.com/Abhishekh-Jha/LDL_Project/blob/main/LDL-C%20powerBI%20Dashboard/dashboard_preview.png)
 Summary: https://github.com/Abhishekh-Jha/LDL_Project/blob/main/LDL-C%20powerBI%20Dashboard/Sumary.png

 How to Run
```bash
git clone https://github.com/Abhishekh-Jha/LDL_Project.git
cd LDL_Project
pip install -r requirements.txt
jupyter notebook notebooks/LDL_Analysis.ipynb
