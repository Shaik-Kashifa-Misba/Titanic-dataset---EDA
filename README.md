# Titanic-dataset---EDA
Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains a comprehensive Exploratory Data Analysis (EDA) performed on the Titanic dataset as part of my Data Analyst Internship at Elevate Labs.

🧠 Objective
To understand the factors influencing passenger survival in the Titanic dataset through statistical and visual analysis using Python.

📦 Files Included

Titanic_EDA_Task.ipynb – Jupyter notebook with full code and visualizations
Titanic_EDA_Report_Final.pdf – PDF summary of findings
README.md – Documentation for this project


🛠 Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

📊 EDA Process
✅ Step 1: Data Loading & Overview
Loaded train.csv from Kaggle Titanic competition
Checked shape, column types, and missing values

✅ Step 2: Data Cleaning
Filled missing values in Age and Embarked
Dropped Cabin due to excessive nulls
Created new feature: FamilySize = SibSp + Parch + 1

✅ Step 3: Univariate Analysis
Analyzed distributions of age, fare, gender, class
Found most passengers were male and in 3rd class

✅ Step 4: Bivariate Analysis
Compared survival with gender, class, and embarkation point
Found women and 1st class passengers had higher survival

✅ Step 5: Multivariate Analysis
Used heatmap and pairplots to study feature correlations
Fare, Pclass, and FamilySize were related to survival


💡 Key Findings
Sex: Females had a much higher survival rate (~75%)
Pclass: 1st class passengers survived more than 2nd and 3rd
Family Size: 2–4 member families had better survival
Fare: Higher fare linked to higher survival
Age: Children had slightly better chances


📈 Visualizations Used
Countplots
Histograms with KDE
Boxplots
Violin plots
Heatmaps
Pairplots


✅ Conclusion
This EDA task demonstrated how to:


Clean and analyze real-world data
Use visualizations to communicate findings
Prepare data for modeling
Dataset Source Titanic - Machine Learning from Disaster (Kaggle)
