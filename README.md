
# 🎓 Student Burnout & Dropout Risk Classification

A Machine Learning classification project designed to identify early warning signs of academic burnout and dropout risk among students based on behavioral, academic, and psychological indicators.

---

## 📌 Project Overview
Early detection of student distress allows academic institutions to intervene before dropout occurs. This project analyzes multi-dimensional student data and applies supervised classification algorithms to predict:
- **Burnout Level** (Categorical / Multi-class)
- **Dropout Risk** (Binary / Multi-class)

---

## 📊 Dataset & Features
The model evaluates key indicators including:
- **Academic Factors:** Year of Study, Department, Previous GPA, Backlogs, Attendance Percent
- **Lifestyle Metrics:** Sleep Hours, Screen Time, Study Hours Per Day, Exercise Frequency
- **Psychological & Social Factors:** Stress Level, Anxiety Score, Peer Pressure, Financial Stress, Family Support

---

## 🛠️ Workflow & Methodology
1. **Data Cleaning & Handling:** 
   - Checking and imputing missing/null values across features.
   - Detecting and removing duplicate records.
2. **Exploratory Data Analysis (EDA):**
   - Correlation analysis between mental health metrics and academic performance.
   - Feature distribution and class balance checks.
3. **Feature Engineering & Preprocessing:**
   - Categorical encoding (One-Hot / Label Encoding).
   - Feature scaling for continuous numerical attributes.
4. **Classification Modeling:**
   - Training baseline classifiers (e.g., Logistic Regression, Decision Trees, Random Forest, XGBoost).
   - Hyperparameter tuning and model optimization.
5. **Evaluation Metrics:**
   - Accuracy, Precision, Recall, F1-Score, and Confusion Matrix analysis to handle potential class imbalances.

---

## 💻 Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Google Colab

---

## 🚀 How to Run
1. Open `Student_burnout_dropout_risk_prediction.ipynb` directly in GitHub or click the **Open in Colab** badge inside the notebook.
2. Run all cells sequentially (`Runtime` > `Run all`).
