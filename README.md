# 🧠 Employee Attrition Prediction (Final ML Project - NYU)

This project uses supervised machine learning models to predict employee attrition using structured HR data. It was developed as part of NYU’s Machine Learning course and received **outstanding feedback from the instructor** for its real-world relevance, robustness, and ethical focus.

## 📄 Abstract

Attrition leads to loss of talent, increased recruitment costs, and lowered productivity. This project leverages models like XGBoost, Random Forest, and Logistic Regression on the IBM HR Analytics dataset to predict which employees are likely to leave, enabling organizations to proactively intervene.

---

## 📁 Contents

- `employee_attrition_prediction.ipynb` — Google Colab notebook with code, EDA, modeling, and evaluation
- `ML_Project_Report.pdf` — Full project report with methods, results, and key insights
- `README.md` — This file

---

## 🏅 Instructor Feedback

> "**Excellent work on this project!** You’ve gone above and beyond expectations in terms of scope, practical applicability, and rigor.  
> Your focus on explainability, fairness, and real-world HR impact is exactly how machine learning should be applied.  
> You’ve clearly understood the purpose of the project, evaluated your model pipeline thoroughly, and thought deeply about interpretation."

---

## 📊 Key Highlights

| Feature                     | Details                                                                 |
|----------------------------|-------------------------------------------------------------------------|
| 📈 Dataset                 | IBM HR Analytics (1,470 records, 34 features)                           |
| 🤖 Models Used             | Logistic Regression, Decision Tree, Random Forest, SVM, XGBoost, CatBoost |
| ⚖️ Class Imbalance Handling | SMOTE, scale_pos_weight, class_weight                                 |
| 📉 Accuracy (Top Model)     | 86% (XGBoost)                                                           |
| 🔍 Interpretability Tools   | SHAP, feature importance                                                |
| 🧠 Business Insight         | Overtime, low income, low satisfaction → top predictors of attrition    |

---

## 🔬 EDA Insights

- Younger employees and those with <2 years at the company had higher attrition.
- Overtime and low job/environment satisfaction were strong behavioral predictors.
- Departments like Sales and roles like Lab Technician faced the highest turnover.
- Commute distance and low income added compounding attrition risks.

---

## ⚙️ Models and Evaluation

Models were evaluated using:
- Accuracy
- F1-Score (focused on minority class: Attrition = Yes)
- ROC-AUC (CatBoost: 0.737, XGBoost: 0.73–0.91)
- Confusion Matrix & Cross-Validation (5-fold stratified)

Ensemble models like **XGBoost and CatBoost** significantly outperformed simpler models.

---

## 🚀 Real-World Application

- Early warning system for at-risk employees
- Strategic compensation, workload, and engagement policy design
- HR dashboard integration for real-time alerts
- Cost-aware talent retention planning

---

## 🔧 Tech Stack

- **Languages:** Python  
- **Libraries:** scikit-learn, pandas, matplotlib, seaborn, imbalanced-learn, XGBoost, CatBoost, SHAP  
- **Notebook:** Google Colab  
- **Dataset:** [IBM HR Analytics](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 📌 Future Enhancements

- Real-time HR data integration  
- Sentiment analysis on internal surveys  
- SHAP/LIME deployment for deeper model explainability  
- Cost-sensitive classification modeling  
- Web dashboard with live inference API

---

## 🙋‍♀️ Author

**Niharika Bhasin**  
Graduate Student, Computer Science  
📧 nb4048@nyu.edu  
📎 [LinkedIn](https://linkedin.com/in/niharika-bhasin)

---

## 📜 References

- [Kaggle Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
- Applied Sciences (2022), JETIR (2020), ResearchGate papers  
- NYU Machine Learning (INT2), Final Project – Spring 2025

