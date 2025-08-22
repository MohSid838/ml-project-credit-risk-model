# 💳 ML Project: Credit Risk Prediction  

This project predicts **credit risk** (whether a loan applicant is low-risk or high-risk) based on applicant details such as income, loan amount, credit history, dependents, and more.  
It integrates **data preprocessing, feature engineering, machine learning models, and deployment** into a complete end-to-end pipeline.  

---

## 🚀 Live Demo  
👉 Try the live app here: [Credit Risk Calculator](https://ml-project-credit-risk-model-calculation.streamlit.app/)  

---

## 📊 Features  

### 🔹 1. Data Cleaning and Preprocessing  
- Handles missing values and categorical encodings.  
- Normalizes and scales numerical features (e.g., income, loan amount).  
- Splits data into **training and testing sets** for unbiased evaluation.  

### 🔹 2. Exploratory Data Analysis (EDA)  
- Statistical summaries of applicant demographics & loan data.  
- Visualization of distributions, correlations, and risk patterns.  
- Insights into how credit history, income, and loan amount impact default risk.  

### 🔹 3. Feature Engineering  
- Derived features such as **Debt-to-Income ratio**.  
- Transformation of categorical variables (education, marital status, property area).  
- Feature importance analysis for risk prediction.  

### 🔹 4. Credit Risk Prediction (ML Models)  
- Classification models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting.  
- Model evaluation using Accuracy, Precision, Recall, F1-Score, ROC-AUC.  
- Selection of the best-performing model for deployment.  

### 🔹 5. Interactive Streamlit Web App  
- User inputs: Applicant’s income, loan amount, dependents, education, credit history, property area, etc.  
- Predicts **Low Risk** or **High Risk** instantly.  
- Shows probability scores and visual insights.  

### 🔹 6. Data Visualization  
- Heatmaps, bar charts, and pie charts for applicant demographics.  
- Confusion matrix & ROC curve for model performance.  
- Loan approval trends across applicant groups.  

---

## 📂 Project Structure  

```
ml-project-credit-risk-model/
│── data/                 # Dataset files
│── notebooks/            # Jupyter notebooks for exploration
│── app.py                # Streamlit application
│── requirements.txt      # Dependencies
│── README.md             # Project documentation
```  

---

## ⚙️ Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/MohSid838/ml-project-credit-risk-model.git
   cd ml-project-credit-risk-model
   ```  

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

3. Run the Streamlit app locally:  
   ```bash
   streamlit run app.py
   ```  

---

## 📈 Results & Insights  
- **Credit history** is the strongest predictor of loan approval.  
- Applicants with higher **income-to-loan ratio** are more likely to be low-risk.  
- Ensemble models (Random Forest, Gradient Boosting) performed better than simple classifiers.  

---

## 🛠️ Tech Stack  
- **Python**, **Pandas**, **NumPy**, **Scikit-learn**  
- **Matplotlib**, **Seaborn** for data visualization  
- **Streamlit** for deployment  
- **GitHub** for version control  

---

## 📬 Contact  
👤 Author: [MohSid838](https://github.com/MohSid838)  
🔗 GitHub Repo: [ml-project-credit-risk-model](https://github.com/MohSid838/ml-project-credit-risk-model)  
