# 🧠 AI-Driven Analysis of Sleep Habits and Student Productivity

## 📌 Overview

This project explores how students' sleep habits influence their academic productivity, specifically **morning class attentiveness**, using Machine Learning techniques.

The study analyzes behavioral and sleep-related data collected through surveys and applies multiple ML models to predict student attentiveness levels.

---

## 🎯 Objectives

* Analyze the relationship between sleep habits and student productivity
* Identify key factors affecting morning attentiveness
* Compare performance of different machine learning models
* Provide data-driven insights for improving student lifestyle

---

## 📊 Dataset

* Collected via **Google Forms survey**
* Includes:

  * Demographic data (age, gender, department)
  * Sleep-related features:

    * Weekday & weekend sleep duration
    * Sleep consistency
    * Nap duration
    * Device usage before sleep
    * Noise sensitivity
    * Skipped classes
    * Negative sleep habits
* Target variable:

  * **Morning_Class_Attentiveness**

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Handling missing values
* Label encoding for categorical features
* Feature scaling (StandardScaler)
* Train-test split (80% / 20%)
* Class balancing (oversampling)

### 2. Models Used

* Logistic Regression
* Random Forest
* Gradient Boosting
* XGBoost
* CatBoost

### 3. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 📈 Results

| Model               | Accuracy  |
| ------------------- | --------- |
| **CatBoost**        | **96.4%** |
| Random Forest       | 91.1%     |
| XGBoost             | 87.9%     |
| Gradient Boosting   | 82.3%     |
| Logistic Regression | 72.5%     |

✅ **CatBoost performed the best**, showing strong capability in handling categorical and behavioral data.

---

## 🔍 Key Insights

* Sleep consistency strongly affects attentiveness
* Weekend sleep duration plays a significant role
* Device usage before bedtime negatively impacts productivity
* Better sleep habits → higher academic performance

---

## 🧪 Explainable AI (XAI)

To interpret model predictions, the following techniques were used:

* SHAP (SHapley Additive Explanations)
* LIME (Local Interpretable Model-Agnostic Explanations)
* Partial Dependence Plots (PDP)

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost, CatBoost
* Matplotlib, Seaborn
* Google Colab

---

## 📁 Project Structure

```
├── data/
│   └── cleaned_sleep_data.csv
├── notebooks/
│   └── self_thesis.ipynb
├── report/
│   └── Thesis_Report.docx
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## ⚠️ Limitations

* Based on self-reported survey data
* Limited sample size and demographic scope
* Focused only on morning attentiveness
* Cannot establish causality (only correlation)

---

## 🔮 Future Work

* Use wearable device data for real-time sleep tracking
* Expand dataset across multiple universities
* Include additional factors (stress, diet, physical activity)
* Build a recommendation system for students

---

## 👨‍💻 Authors

* MD Kamran Hussen
* MD Shahir Sammun
* Nuzat Rahman

Supervisor: Md. Arifuzzaman

---

## 📜 License

This project is for academic and research purposes.
