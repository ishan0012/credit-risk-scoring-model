# 💳 Credit Risk Scoring & Default Prediction System

## 🚀 Project Overview
This project addresses a critical challenge in the banking sector: **Predicting Loan Default Risk**. By analyzing 5,000+ synthetic applicant records, I developed a Machine Learning pipeline that identifies high-risk borrowers based on financial behavior, credit history, and debt-to-income ratios.

## 🛠️ Tech Stack
- **Language:** Python
- **Machine Learning:** Scikit-Learn (Random Forest)
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Seaborn, Matplotlib

## 📈 Key Features & Methodology
1. **Financial Feature Engineering:** Created a custom **Debt-to-Income (DTI)** ratio, a key industry metric for assessing repayment capacity.
2. **Class Imbalance Management:** Utilized `class_weight='balanced'` within the Random Forest algorithm to ensure accurate detection of the minority "Default" class (15% of data).
3. **Data Scaling:** Implemented `StandardScaler` to normalize financial features, ensuring stable model convergence.
4. **Interpretability:** Generated a Feature Importance map to identify the top drivers of credit risk (Credit Score and DTI Ratio).

## 📁 Repository Structure
- `credit_risk_analysis.ipynb`: The end-to-end Python notebook.
- `credit_risk_data.csv`: The generated dataset used for training.
- `requirements.txt`: List of necessary Python libraries.

