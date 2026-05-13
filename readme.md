# Employee Performance Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting employee performance using Machine Learning techniques. The workflow includes data cleaning, exploratory data analysis (EDA), feature importance analysis, and classification using a Random Forest model.

The goal of this project is to identify the key factors affecting employee performance and build a predictive model for performance classification.

---

# 📂 Dataset Information

* Dataset Size: **100,000 rows**
* Features: **20 columns**
* Target Variable: **Performance_Score**

The dataset contains employee-related information such as:

* Monthly Salary
* Job Title
* Department
* Training Hours
* Employee Satisfaction Score
* Years at Company
* Overtime Hours
* Projects Handled
* Gender
* Promotions
* and more.

---

# ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed to analyze relationships between employee performance and different features.

### Key Analyses:

* Salary vs Performance
* Satisfaction Score vs Performance
* Age vs Performance
* Experience vs Performance
* Training Hours vs Performance
* Department-wise Performance
* Gender-wise Performance
* Correlation Heatmap
* Feature Importance Analysis

---

# 🔍 Key Insights

* **Monthly Salary** was the most influential feature affecting employee performance.
* **Job Title** also showed strong predictive importance.
* Most other features showed weak individual correlations with the target variable.
* Department-wise and gender-wise performance distributions appeared nearly uniform.

---

# 🤖 Machine Learning Model

### Model Used:

* Random Forest Classifier

### Workflow:

1. Data Cleaning
2. Label Encoding
3. Train-Test Split
4. Model Training
5. Prediction
6. Evaluation
7. Feature Importance Analysis

---

# 📈 Model Performance

The Random Forest model achieved extremely high accuracy on the dataset.

### Evaluation Metrics:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

# ⚠️ Important Observation

During EDA and model evaluation, the dataset appeared highly balanced and potentially synthetic/rule-based because:

* The model achieved near-perfect accuracy.
* Feature distributions were unusually uniform.
* Salary strongly dominated prediction importance.

This project highlights not only model building but also critical dataset analysis and interpretation.

---

# 📁 Project Structure

```bash
ML8-Employee-Performance-Prediction/
│
├── data/
│   └── employee_data.csv
│
├── notebook.ipynb
├── README.md
├── requirements.txt
│
└── screenshots/
```

---

# 🚀 Future Improvements

* Use real-world HR datasets
* Try XGBoost and LightGBM
* Hyperparameter tuning
* Build deployment-ready web app
* Perform advanced feature engineering

---

# 📌 Conclusion

This project demonstrates a complete machine learning workflow including:

* Data preprocessing
* Exploratory Data Analysis
* Feature importance analysis
* Classification modeling
* Critical evaluation of dataset behavior

It also emphasizes the importance of understanding data quality and detecting potentially synthetic patterns in datasets.

---

# 👨‍💻 Author

Pranay Gaur
