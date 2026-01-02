
# 🎓 Student Performance Prediction – Machine Learning Project

## 📌 Project Overview
This project applies **Machine Learning techniques** to analyze and predict **student academic performance** using a real-world dataset containing **20,000+ records** and **40+ features** related to academic, behavioral, psychological, and socio-economic factors.

The project includes:
- **Regression** for predicting final scores  
- **Binary classification** for Pass / Fail prediction  
- **Multiclass classification** for Final Grade prediction  
- An **interactive model comparison dashboard** built using **Streamlit**

> ⚠️ **Note:** The comparison dashboard was **not a project requirement**. It was added as an **extra feature** to enhance model evaluation and to gain hands-on experience in building ML dashboards.

---

## 📂 Dataset
- **File:** `Term_Project_Dataset_20K.csv`
- **Size:** ~20,000 samples
- **Features:** 40+ input features + target variables
- **Targets Used:**
  - `final_score` (Regression)
  - `pass_fail` (Binary Classification)
  - `final_grade` (Multiclass Classification)

---

## 🔍 Project Objectives
- Understand the impact of multiple factors on student performance  
- Compare different ML models across regression and classification tasks  
- Evaluate models using appropriate performance metrics  
- Present results clearly using **visualizations and dashboards**

---

## 🧠 Machine Learning Models
### Regression
- Linear Regression  
- Ridge & Lasso Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

**Evaluation Metrics:**  
MAE, MSE, RMSE, R²

### Binary Classification
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  
- Random Forest Classifier  

**Evaluation Metrics:**  
Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix

### Multiclass Classification
- KNN Classifier  
- Decision Tree Classifier  
- Random Forest Classifier  

**Evaluation Metrics:**  
Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## 📊 Extra Feature: Model Comparison Dashboard
An **interactive Streamlit dashboard** was developed to:
- Compare regression models side-by-side
- Visualize classification performance metrics
- Display confusion matrices and ROC curves
- Make model evaluation easier and more intuitive

This dashboard was created as a **learning extension beyond course requirements**, helping build skills in:
- ML result visualization  
- Dashboard design  
- Model comparison and interpretation  

---

## 🛠 Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Streamlit  

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone <your-github-repo-link>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit dashboard:
   ```bash
   streamlit run app.py
   ```

---

## 📁 Repository Structure
```
├── dataset/
│   └── Term_Project_Dataset_20K.csv
├── notebooks/
│   └── Final_project.ipynb
├── app.py                # Streamlit dashboard
├── requirements.txt
└── README.md
```

---

## 🎯 Key Learning Outcomes
- Built and evaluated multiple ML models for different prediction tasks  
- Learned how to compare models using suitable metrics  
- Gained hands-on experience with **Streamlit dashboards**  
- Improved understanding of ML pipelines and result communication  

---

## 📌 Future Improvements
- Feature selection and dimensionality reduction  
- Hyperparameter optimization using advanced search techniques  
- Model explainability (SHAP / feature importance)  
- Deployment of the dashboard online  

---

## 🤝 Acknowledgment
This project was completed as part of an academic Machine Learning course and extended beyond the requirements for learning purposes.
