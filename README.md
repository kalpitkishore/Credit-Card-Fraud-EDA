# Credit Card Fraud Detection: Exploratory Data Analysis & Risk Report

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Business Overview
Credit card fraud causes severe financial loss and operational chargeback overhead. This project performs an end-to-end Exploratory Data Analysis (EDA) on a dataset of 556,000+ credit card transactions to identify key behavioral fraud signatures, analyze class imbalance, and propose preprocessing strategies for machine learning models.

## 📊 Key Insights & Business Findings
* **Severe Class Imbalance:** Fraudulent transactions account for $<1\%$ of total transactions, necessitating evaluation via Precision-Recall AUC (PR-AUC) rather than accuracy.
* **High-Value Risk Gradient:** Transactions exceeding **$500** exhibit a significantly higher fraud rate compared to baseline purchasing patterns.
* **Temporal Off-Hours Spike:** While total transaction volume peaks during daytime hours, peak fraud rates occur during late-night windows (**22:00 – 04:00**).
* **High-Risk Channels:** Online/digital channels (`shopping_net`, `misc_net`) show a higher proportion of fraud relative to total volume compared to physical retail transactions.

## 📁 Repository Structure
* `notebooks/`: Executed Jupyter Notebook containing step-by-step EDA, data cleaning, and visualizations.
* `reports/`: Executive summary and risk analysis report.
* `requirements.txt`: Python package dependencies.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Wrangling:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/kalpitkishore/Credit-Card-Fraud-EDA.git](https://github.com/kalpitkishore/Credit-Card-Fraud-EDA.git)