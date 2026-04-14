![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-lightgrey)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-blueviolet)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-f7931e?logo=scikit-learn&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![ML](https://img.shields.io/badge/Machine%20Learning-Model-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Made With](https://img.shields.io/badge/Made%20With-Scikit--Learn-orange)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)


# 🎓 EduPredict – Student Performance Analysis & Prediction

## 📌 Overview

EduPredict is a Machine Learning project focused on analyzing student academic behavior and predicting their performance.
The project explores how factors like attendance, study habits, assignments, and assessments influence final outcomes.

This project goes beyond basic modeling by emphasizing **feature selection, data cleaning, and real-world interpretation of results**.

---

## 🚀 Key Highlights

* Built a complete ML pipeline from raw data to evaluation
* Identified and removed **data leakage issues**
* Performed **feature selection for optimal performance**
* Achieved significant improvement in model accuracy (R² from negative to ~0.64)
* Visualized model performance using **Actual vs Predicted plots**

---

## 📊 Dataset Description

The dataset includes multiple factors affecting student performance:

### 🎯 Academic Features

* Attendance (%)
* Midterm Score
* Assignments Average
* Quizzes Average
* Participation Score
* Projects Score

### 🧠 Behavioral Features

* Study Hours per Week
* Sleep Hours per Night
* Stress Level

### 👤 Demographic Features (optional)

* Age
* Gender
* Department

---

## 🧹 Data Preprocessing

* Removed irrelevant columns:

  * Student_ID, Name, Email
* Handled **data leakage** by removing:

  * Total_Score, Grade
* Cleaned and structured dataset for modeling
* Selected meaningful features based on correlation and impact

---

## 🧠 Feature Engineering

* Focused on **high-impact academic features**
* Reduced noise by eliminating unnecessary columns
* Experimented with different feature combinations to improve performance

---

## 🤖 Model Training

* Used **Linear Regression** as baseline model
* Applied train-test split (80/20)
* Evaluated model performance using multiple metrics

---

## 📈 Evaluation Metrics

* Mean Absolute Error (MAE): ~3.8
* Mean Squared Error (MSE): ~19.18
* Root Mean Squared Error (RMSE): ~4.37
* R² Score: ~0.64

👉 Model improved significantly from poor performance to a stable predictive system

---

## 📊 Visualizations

* 📈 Actual vs Predicted Scatter Plot
* 📉 Residual Analysis
* 📊 Correlation Heatmap
* 📌 Feature Impact Analysis

👉 These visualizations help in understanding:

* Model accuracy
* Error distribution
* Feature relationships

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## ▶️ How to Run

```bash
git clone https://github.com/amansharma2005/EduPredict-Student-Performance-ML-Model.git
cd EduPredict-Student-Performance-ML-Model
pip install -r requirements.txt
jupyter notebook
```

---

## 📌 Key Learnings

* Importance of **feature selection over model complexity**
* Impact of **data leakage on model performance**
* How to interpret ML results using visualization
* Practical understanding of regression metrics

---

## 🚀 Future Improvements

* Implement Random Forest / XGBoost for better accuracy
* Hyperparameter tuning
* Deploy model using Streamlit
* Build interactive dashboard
* Add real-time prediction system

---

## ⭐ Support

If you found this project helpful, consider giving it a star ⭐

---

## 👨‍💻 Author

Aman Sharma

AI/ML/DS  Engineer
