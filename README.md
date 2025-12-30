# Customer Churn Prediction using Machine Learning

## Project Overview
This project aims to predict **customer churn** for a telecom company using machine learning. Churn prediction helps businesses identify customers who are likely to leave, enabling proactive retention strategies.

---

## Dataset
- **Source:** Internal telecom dataset  
- **Number of records:** 20,000 customers  
- **Columns:** 226 features including mobile usage, internet usage, ARPU, last activity dates, and social media usage.  
- **Target Variable:** `churn` (1 = customer left, 0 = customer stayed)  

> **Note:** The dataset contains anonymized customer data.  

---

## Objective
- Predict which customers are likely to churn.  
- Identify key factors contributing to churn.  
- Improve business retention strategies.

---

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn)  
- Google Colab (with T4 GPU)  
- Jupyter Notebook  

---

## Approach
1. **Data Preprocessing:**  
   - Handle missing values  
   - Encode categorical features  
   - Feature scaling  
2. **Exploratory Data Analysis (EDA):**  
   - Visualize churn distribution  
   - Analyze correlation between features and churn  
3. **Model Building:**  
   - Train multiple models (Logistic Regression, Random Forest, XGBoost)  
   - Evaluate performance using precision, recall, F1-score, and accuracy  
4. **Model Evaluation:**  
   - Confusion matrix analysis  
   - Feature importance identification  

---

## Models and Results
| Model                | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.91     | 0.82      | 0.44   | 0.57     |
| Random Forest       | 0.94     | 0.95      | 0.46   | 0.58     |
| XGBoost             | 0.94     | 0.95      | 0.46   | 0.58     |

> Weighted average F1-score of the best model: **0.93**  

---

## Business Insights
- Customers with low usage and low ARPU are more likely to churn.  
- Social media usage and internet activity show minor correlation with churn.  
- Proactive retention strategies should target high-risk customers identified by the model.  

---

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/ML-Customer-Churn-Prediction.git
