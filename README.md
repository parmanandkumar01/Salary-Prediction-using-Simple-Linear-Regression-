# Salary Prediction using Linear Regression

A clean, beginner-friendly machine learning project implementing **Simple Linear Regression** from scratch using Python, scikit-learn, and popular data science libraries to predict employee salaries based on years of experience.

---

## 📊 Project Overview
This project explores the relationship between professional experience and salary compensation. Using a dataset of 30 samples, we perform exploratory data analysis (EDA), check for data integrity (nulls/duplicates), evaluate variable distributions, and train a Linear Regression model to make accurate predictions.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Numerical Operations:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (`LinearRegression`, `train_test_split`, evaluation metrics)

---

## 📂 Dataset Details
* **Source:** `Dataset/Salary_dataset.csv`
* **Dimensions:** 30 rows, 2 columns
* **Features:**
  * `YearsExperience` (float64): The number of years of professional experience an employee has.
  * `Salary` (float64): The corresponding salary compensation.

---

## 📈 Exploratory Data Analysis (EDA) & Insights
* **Data Quality Check:** Verified that there are **0 missing values** and **0 duplicate entries** in the dataset.
* **Outlier Analysis:** 
  * Sorted extreme ends of the dataset to validate data validity (e.g., salaries ranging from $\approx \$37,000$ for entry-level to $\approx \$122,000$ for senior levels).
  * **Conclusion:** High-end values reflect natural workforce distribution rather than data entry errors; hence, they were retained to preserve senior-level patterns.
* **Correlation:** Strong positive linear correlation ($\approx 0.98$) observed between years of experience and salary.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
