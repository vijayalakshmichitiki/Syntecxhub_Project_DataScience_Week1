# Titanic Dataset Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset to understand the factors that influenced passenger survival. The analysis focuses on demographic features such as gender, passenger class, and age.

This project was completed as part of the **Data Science Internship at Syntecxhub**.

---

## 📂 Dataset
- Dataset: Titanic Dataset
- Source: Publicly available Titanic dataset
- Rows: 891
- Columns: 15

---

## 🧹 Data Cleaning & Preprocessing
The dataset contained missing values in the following columns:
- **Age**: 177 missing values → filled using median
- **Embarked / Embark_town**: 2 missing values → filled using mode
- **Deck**: 688 missing values → dropped due to excessive missing data

After preprocessing, the dataset was clean and ready for analysis.

---

## 📊 Exploratory Data Analysis
The following analyses and visualizations were performed:
- Survival rate comparison by **Gender**
- Survival rate comparison by **Passenger Class**
- Survival analysis across **Age Groups**
- Boxplot showing **Age vs Survival**

Visualization tools used:
- Bar charts
- Box plots

---

## 🔍 Key Insights
- Female passengers had a significantly higher survival rate than males.
- Passengers traveling in First Class had the highest survival probability.
- Children showed better survival chances compared to adults.
- Older passengers had comparatively lower survival rates.
- Passenger class played a major role in survival outcomes.

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---
Syntecxhub_Titanic_EDA/
│
├── Titanic_EDA.ipynb
├── README.md
└── images/

---

## 🚀 Conclusion
This EDA helped uncover important survival patterns in the Titanic disaster and demonstrated practical data cleaning, visualization, and analytical skills essential for real-world data science projects.

---

## 🔗 Internship Credit
Completed as part of the **Data Science Internship Program at Syntecxhub**.

