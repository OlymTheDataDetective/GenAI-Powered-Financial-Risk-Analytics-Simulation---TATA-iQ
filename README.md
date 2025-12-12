# Tata iQ – GenAI-Powered Data Analytics & Credit Risk Strategy Simulation (Forage) - December 2025

This project was completed as part of the **Tata iQ GenAI-Powered Data Analytics Job Simulation** on Forage in December 2025.  
It demonstrates an end-to-end, AI-supported workflow for analyzing credit risk data, proposing predictive modeling logic and designing an ethical, scalable collections strategy.

---

## 📂 Project Overview
The objective of this simulation was to assess credit card delinquency risk using a combination of **Excel**, **Python (for metric validation)** and **GenAI** for analytical guidance, model logic, and strategic decision-making.

The project included:
- Exploratory Data Analysis (EDA)
- Predictive model planning (no-code framework)
- Logistic Regression prototype evaluation
- AI-driven strategy design for collections operations

---

## 📊 Dataset
The dataset consisted of:
- **17 customer features**, covering:
  - Demographics (Age, Employment Status, Location)
  - Financial metrics (Income, Credit Score, DTI, Loan Balance)
  - Behavioral signals (Credit Utilization, Missed Payments, Account Tenure)
  - Monthly payment history (**Month_1–Month_6**)

Total records analyzed: *confidential per simulation*, worked with sample of 500 rows for prototype testing.

---

## 🔍 Exploratory Data Analysis (EDA)
Using Excel and GenAI, the following tasks were performed:

### ✔ Data Quality Assessment  
- Identified missing values in `Income` and `Credit_Score`  
- Imputed values using mean based on missing values < 10% distribution analysis
- Standardized inconsistent categories (e.g., Employment_Status)  
- Checked for potential outliers and unusual value patterns  

### ✔ Key Risk Indicators Identified  
- High **Credit Utilization**  
- Multiple **Missed Payments**  
- High **Debt-to-Income Ratio**  
- Low **Credit Score**  
- Declining payment behavior across Month_1–Month_6  

---

## 🤖 Predictive Modeling Framework (No-Code)

GenAI was used to design a predictive modeling approach:
- Selected **Logistic Regression** for interpretability and regulatory alignment  
- Outlined feature set:  
  `Credit_Utilization`, `Missed_Payments`, `Income`, `Debt_to_Income_Ratio`, `Account_Tenure`  
- Defined evaluation metrics: **precision, recall, F1-score, AUC**  

### 📈 Logistic Regression Prototype (Python Evaluation)
A prototype evaluation was performed to understand feasibility:

| Metric     | Score |
|------------|--------|
| Accuracy   | 0.43   |
| Precision  | 0.12   |
| Recall     | 0.50   |
| F1 Score   | 0.20   |
| AUC        | 0.48   |

**Key Insight:**  
High recall (50%) for delinquent cases indicates some sensitivity, but low precision and AUC show model instability due to class imbalance and limited feature richness.

---

## 🤝 AI-Driven Collections Strategy

Based on model insights and customer risk segmentation, an AI-enabled collections strategy was designed:

### ✔ Strategy Components
- Early outreach for high-risk segments  
- Use of agentic AI for automated reminders and workflow triggers  
- Personalized communication paths  
- Integration of explainable risk scoring  

### ✔ Ethical AI & Compliance
- Fairness checks across age, income, and demographic groups  
- Transparent model logic (Logistic Regression coefficients)  
- Non-discriminatory and supportive intervention design  
- Alignment with financial regulatory standards  

---

## 🛠 Tools & Technologies
- **Excel** (Data cleaning, analysis)
- **Python** (Model metric evaluation)
- **GenAI / ChatGPT** (EDA insights, modeling logic, strategy development)

---

## 📌 Key Takeaways
- Established a repeatable, AI-assisted workflow for credit risk analysis  
- Built a transparent modeling framework suitable for financial institutions  
- Demonstrated responsible and ethical use of GenAI in risk-driven decision-making  
- Delivered actionable recommendations for improving collections performance  

---

## 📁 Project Structure
├── README.md
│
├── data/
│   └── raw_dataset.xlsx                # Original dataset provided for analysis
│
├── eda/
│   ├── eda_summary.docx                # Written EDA report from the simulation
│   └── eda_summary.xlsx                # Excel file used for data cleaning and EDA
│
├── model/
│   ├── logistic_regression.ipynb       # Jupyter Notebook with model logic & evaluation
│   └── model_summary.docx              # Written summary explaining model approach



## 👤 Author
**Olympia Devi Gurumayum**  
Data Analyst | Python • Excel • GenAI   

---

## ⭐ Acknowledgments
This project is part of the **Tata iQ – GenAI-Powered Data Analytics Simulation** hosted by Forage.
