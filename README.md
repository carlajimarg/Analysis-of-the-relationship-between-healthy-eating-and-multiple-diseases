# Analysis of the Relationship Between Healthy Eating and Multiple Diseases

Academic group project developed as part of the Data Science degree at UPV (2024-2025).

## 📌 Overview
Analysis of the relationship between dietary habits, economic development and chronic 
diseases across European and American countries. The study integrates 5+ datasets 
from sources including WHO, Eurostat, Kaggle and IHME, covering variables such as 
obesity, diabetes, cardiovascular disease, hypertension, life expectancy and caloric intake.

## 🛠️ Technologies
- **Language:** R / RStudio
- **Libraries:** ggplot2, dplyr, FactoMineR, cluster, DataExplorer
- **Techniques:** K-Means Clustering (Elbow Method), PCA, Pearson/Spearman 
  Correlation, Linear & Non-linear Regression, Silhouette Score, Hierarchical 
  Clustering (Ward's Method)

## 📊 Datasets
Data sourced from WHO, Eurostat, Kaggle, DBnomics and IHME:
- GDP per capita & Life Expectancy (2000–2015)
- Obesity prevalence (1990–2021) and Diabetes by country (1980–2014)
- Daily caloric intake by food group (2000–2018)
- Cardiovascular disease & Hypertension prevalence (PAHO/WHO)
- Alcohol consumption and Drug use (IHME)
- Physical inactivity prevalence (WHO)

## 🔍 Key Findings
- Strong positive correlation (r = 0.73) between obesity and diabetes prevalence 
  across American countries
- HDI and GDP per capita are significant predictors of dietary variety (p < 0.01); 
  countries with higher HDI consume more animal-source calories
- A non-linear regression model explained 70% of HDI variability using life 
  expectancy, animal kcal intake and thinness
- Physical inactivity shows the strongest association with obesity (r = 0.53) 
  among lifestyle factors studied
- 3 distinct dietary-health profiles identified in American countries via clustering, 
  linked to differences in life expectancy

## 👥 Authors
- Carla Jimenez Argudo
- Marta Martínez Martínez
- Michele Romero Calero
- Fernanda De Paula Gonçalves
- Mario Álvarez Martínez
