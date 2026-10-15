# Salary Prediction using Linear Regression

A clean, beginner-friendly machine learning project implementing **Simple Linear Regression** from scratch using Python, scikit-learn, and popular data science libraries to predict employee salaries based on years of experience.

---

## 📊 Project Overview
This project explores the relationship between professional experience and salary compensation. Using a dataset of 30 samples, we perform exploratory data analysis (EDA), check for data integrity (nulls/duplicates), evaluate variable distributions, and train a Linear Regression model to make accurate predictions[cite: 1].

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python[cite: 1]
* **Data Manipulation & Numerical Operations:** Pandas, NumPy[cite: 1]
* **Data Visualization:** Matplotlib, Seaborn[cite: 1]
* **Machine Learning:** Scikit-Learn (`LinearRegression`, `train_test_split`, evaluation metrics)[cite: 1]

---

## 📂 Dataset Details
* **Source:** `Dataset/Salary_dataset.csv`[cite: 1]
* **Dimensions:** 30 rows, 2 columns[cite: 1]
* **Features:**
  * `YearsExperience` (float64): The number of years of professional experience an employee has[cite: 1].
  * `Salary` (float64): The corresponding salary compensation[cite: 1].

---

## 📈 Exploratory Data Analysis (EDA) & Insights
* **Data Quality Check:** Verified that there are **0 missing values** and **0 duplicate entries** in the dataset[cite: 1].
* **Outlier Analysis:** 
  * Sorted extreme ends of the dataset to validate data validity (e.g., salaries ranging from $\approx \$37,000$ for entry-level to $\approx \$122,000$ for senior levels)[cite: 1].
  * **Conclusion:** High-end values reflect natural workforce distribution rather than data entry errors; hence, they were retained to preserve senior-level patterns.
* **Correlation:** Strong positive linear correlation ($\approx 0.98$) observed between years of experience and salary[cite: 1].

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
