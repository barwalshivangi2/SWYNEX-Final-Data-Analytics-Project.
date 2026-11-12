# SWYNEX-Final-Data-Analytics-Project.
# 🚢 Titanic Survival - Final Data Analytics Case Study

## 📌 Problem Statement
The objective of this project is to analyze the Titanic passenger dataset to understand the demographics and factors influencing survival rates, and to build an interactive web dashboard for real-time data exploration.

## 🗂️ Dataset Information
* **Source:** SWYNEX Technologies Internship
* **Records:** 889 passengers (after cleaning)
* **Key Variables:** Survived, Pclass, Sex, Age, Fare, Embarked.

## 🧹 Data Cleaning Process
* Handled missing values in 'Age' using median imputation.
* Dropped the highly sparse 'Cabin' column.
* Removed duplicates and standardized categorical columns for consistency.

## 📊 Exploratory Data Analysis (EDA)
* Analyzed survival rates across different genders and passenger classes.
* Identified correlations between ticket fare and survival probability.

## 📈 Interactive Dashboard
Built a custom dark-themed web dashboard using **Python, Streamlit, and Plotly**.
* Features dynamic KPIs, 3D metric cards, interactive pie charts, and bar graphs.
* Allows active filtering by 'Embarked' city.

## 💡 Key Business Insights
1. **Gender Impact:** Females had a significantly higher survival rate (~74%) compared to males.
2. **Class Priority:** First-class (Pclass 1) passengers had the highest likelihood of survival, indicating prioritization during the rescue operations.
3. **Actionable Takeaway:** In historical emergency protocols, demographic and socio-economic prioritization drastically impacted survival outcomes.
