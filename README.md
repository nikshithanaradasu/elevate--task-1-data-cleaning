# 🚀 Task 1: Data Cleaning & Preprocessing – Elevate Internship

## 📄 Objective
Clean and preprocess a raw dataset (Titanic) to make it ready for Machine Learning models.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn

---

## 🔢 Steps Followed

1. **Data Loading & Exploration**
   - Loaded Titanic dataset
   - Identified missing values, datatypes

2. **Handling Missing Values**
   - Filled `Age` with median
   - Filled `Embarked` with mode
   - Dropped `Cabin` due to high null count

3. **Encoding Categorical Data**
   - Used Label Encoding for `Sex`
   - One-Hot Encoded `Embarked`

4. **Feature Scaling**
   - Standardized `Age` and `Fare` using `StandardScaler`

5. **Outlier Detection**
   - Visualized using boxplots
   - Removed outliers using IQR method

6. **Final Output**
   - Cleaned dataset saved as `cleaned_titanic.csv`

---

## 📈 Sample Visualizations
- Survival Count
- Survival Rate by Gender

---

## 🧠 What I Learned
- Handling different types of missing values
- Encoding techniques: Label vs One-Hot
- Normalization vs Standardization
- Outlier detection and handling
- Importance of preprocessing in ML

---

## ✅ Status
Task 1 completed successfully! 🚀
