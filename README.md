# EDA_Heart_Disease_Analysis
This repository contains a detailed analysis of heart disease data, focused on identifying patterns and relationships among key health indicators. The project uses Python and a variety of data science tools to examine the relationship between age, gender, type of chest pain, fat levels, and other factors
## Overview
This project analyzes a heart disease dataset to extract meaningful insights related to cardiovascular health indicators. The dataset contains demographic, clinical, and diagnostic attributes, focusing on identifying patterns that may correlate with the presence of heart disease.
## Features Analyzed
The following columns were primarily analyzed in this notebook:
1.	Age: Patient's age in years.
2.	Sex: Gender of the patient (1 = Male, 0 = Female).
3.	CP (Chest Pain Type):
  o	Typical Angina
  o	Atypical Angina
  o	Non-Anginal Pain
  o	Asymptomatic
4.	Trestbps: Resting blood pressure (in mmHg).
5.	Chol: Serum cholesterol levels (in mg/dL).
6.	Exang: Exercise-induced angina (1 = Yes, 0 = No).
7.	Num: Diagnosis of heart disease (0 = No disease, 1-4 = Severity levels).
## Analysis Objectives
The primary goals of this analysis were:
•	To identify statistical trends and correlations among the features.
•	To investigate the relationship between heart disease severity (num) and other attributes like chest pain type, cholesterol, and blood pressure.
•	To highlight potential risk factors based on demographic and clinical data.
## Key Findings
1.	Blood Pressure and Cholesterol:
o	Average resting blood pressure: ~132 mmHg.
o	Average cholesterol level: ~199 mg/dL, with a wide range indicating variability among individuals.
2.	Gender and Age Distribution:
o	Males show a higher prevalence of severe heart disease compared to females.
o	The age group around 53-54 years is most represented, suggesting midlife as a critical risk period.
3.	Chest Pain and Exercise Angina:
o	Asymptomatic individuals often report exercise-induced angina, highlighting a potential link between these attributes.
## Dataset Details
•	Row Count: 920 entries.
•	Column Count: 16 features.
•	Data Types: A mix of numerical and categorical attributes.
## Recommendations for Future Work
•	Explore additional features like thalach (maximum heart rate) and oldpeak (ST depression) for deeper insights.
•	Implement machine learning models to predict heart disease severity based on the available data.
•	Address missing values in features like slope, ca, and thal for better accuracy.
