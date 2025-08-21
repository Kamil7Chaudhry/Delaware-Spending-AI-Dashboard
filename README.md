# Delaware-Spending-AI-Dashboard
AI-powered dashboard to analyze Delaware state spending and detect anomalous or potentially fraudulent transactions.


## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Detected Anomalies](#detected-anomalies)
- [Architecture](#architecture)
- [Demo](#demo)
- [Contact](#contact)

---

## Project Overview
I have analyzed **10 years of Delaware state spending data** from [Delaware Open Checkbook](https://opencheckbook.delaware.gov/#!/year/2025/).  

I've built an **AI-powered dashboard** that:  
- Flags suspicious transactions  
- Detects duplicates and unusual payments  
- Highlights potential fraud  
- Provides interactive charts and visualizations  

---

## Features
- Real-time anomaly detection  
- Interactive dashboard using Streamlit / Plotly  
- Customizable thresholds for anomalies  
- Exportable flagged transactions  

---

## Dataset
- Source: [Delaware Open Checkbook 2025](https://opencheckbook.delaware.gov/#!/year/2025/)  
- Includes millions of transactions: payee, amount, date, and funding source  

---

## Detected Anomalies
The dashboard flags **5 types of anomalies**:
1. Duplicate payments  
2. Transactions on holidays  
3. Outlier amounts  
4. Negative Transactions 
5. Late Transactions 

---

## Architecture
- **Data Cleaning:** Python scripts (`src/data_cleaning.py`)  
- **Anomaly Detection:** Python ML models (`src/anomaly_detection.py`)  
- **Dashboard:** Streamlit / Plotly / Looker Studio  
- **Reporting:** Export CSV files of flagged transactions  

---

## Demo
Live dashboard: [Google Looker Studio Dashboard](https://lookerstudio.google.com/u/0/reporting/fb20cc41-e739-4cf3-b24c-b0e0f4592184/page/FbfUF)  

---

## Contact
**Kamil Kamil Munir Chaudhry**  
Email: kamilch@udel.edu
GitHub: [https://github.com/YourUsername](https://github.com/YourUsername)
