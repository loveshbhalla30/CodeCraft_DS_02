# CodeCraft_DS_02
This repository contains a Jupyter Notebook for the Data Science project.
📌 Problem Statement The Titanic dataset is a classic dataset in data science, often used to explore classification problems. The objective here is to analyze the passenger data to understand the survival patterns based on various demographic and economic factors like age, sex, class, and fare.

🎯 Objective Perform exploratory data analysis (EDA) on Titanic passenger data.

Identify how different features like gender, passenger class, and age groups affect survival rates.

Use plots to visually highlight insights and trends.

🧠 Approach / How I Solved It Data Loading & Inspection:

Loaded the Titanic dataset using Pandas.

Inspected shape, data types, and missing values.

Data Cleaning & Preprocessing:

Checked and summarized missing values.

Created a new column AgeGroup to categorize passengers by age.

Visualization:

Used Seaborn and Matplotlib for detailed visual insights:

Bar plots for survival count, survival by gender, and class.

Histogram and KDE for age and fare distribution.

Grouped survival stats based on AgeGroup.

Insights:

Females had a significantly higher survival rate.

Passengers from higher classes were more likely to survive.

Children had higher survival chances than adults and seniors.

📊 Technologies & Tools Used Python

Jupyter Notebook

Pandas

Matplotlib

Seaborn
