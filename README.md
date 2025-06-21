# 🛳️ Titanic Dataset - Exploratory Data Analysis (EDA)

Exploratory Data Analysis on Iris &amp; Titanic datasets using Pandas, Seaborn, and Matplotlib.

This project explores the famous **Titanic dataset** using Python libraries like Pandas, Seaborn, and Matplotlib. The goal is to uncover patterns in the data—particularly factors that influenced passenger survival.

## 📁 Dataset Used
- [`train.csv`](https://www.kaggle.com/competitions/titanic/data) from the Kaggle Titanic competition

## 🔍 Key Objectives
- Understand the dataset structure
- Handle missing values (e.g., Age imputation)
- Visualize survival rates by gender, class, and age
- Prepare data for upcoming machine learning tasks

## 📊 Techniques Used
- **Missing value handling** (mean imputation for `Age`)
- **Data visualization**:
  - Count plots for `Survived`, `Sex`, `Pclass`
  - Combined plots: `Pclass` × `Survived` × `Sex`
  - KDE plots for age and survival
- **Feature insights**:
  - Dropped irrelevant columns (`Cabin`)
  - Observed strong survival correlation with `Sex` and `Pclass`

## 📘 Libraries
- Python
- Pandas
- Seaborn
- Matplotlib

## 💡 Key Findings
- Females had a much higher survival rate than males.
- Passengers in 1st class were more likely to survive.
- Age did not show a strong individual pattern, but young children had higher survival.

## ✅ Next Steps
- Use insights from this EDA to build a **classification model** (e.g., Logistic Regression) in Week 2.

---

> 🎓 Part of a structured 8-week Machine Learning roadmap for internship preparation.
