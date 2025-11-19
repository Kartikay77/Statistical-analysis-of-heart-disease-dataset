# Statistical-analysis-of-heart-disease-dataset
1. Performed Simple Linear regression on the dataset column of Age vs Cholesterol
2. Performed Chi-square test on ChestPain with target & also made a bar graph
3. Estimating PopulationMean with Confidence Interval for Blood Pressure
4. Estimating Population Proportion with Confidence Interval Interprestation
5. Estimating Difference Between PopulationMeans with Confidence Interval
6. Estimating Difference in Proportions with Confidence Interval
7. Hypothesis Testing and Visualizations
   7.1 PopulationMean Hypothesis Test - SerumCholesterol
   7.2 Population Proportion Hypothesis Test - Gender
   7.3 Difference Between PopulationMeans Hypothesis Test - Age and Heart Disease
   7.4 Difference Between Population Proportions Hypothesis Test - Fasting Blood Sugar and Heart Disease
8. Analysis of Variance (ANOVA) Results

# Overview
This project explores the UCI Heart Disease dataset using classical statistical techniques.  
It applies regression, hypothesis testing, confidence intervals, and ANOVA  
to identify factors strongly associated with heart disease risk.

## Tools Used
- R, RMarkdown  
- ggplot2, corrgram  
- Base R statistical tests (t-tests, ANOVA, Chi-square)  
- dplyr for data wrangling  


## Project Overview
This project performs complete statistical analysis on the UCI Heart Disease dataset, including:
1. Simple Linear Regression (Age vs Cholesterol)
2. Chi-square test (ChestPain vs Target)
3. Confidence Intervals for:
   - Population Mean (Blood Pressure)
   - Population Proportion
4. Difference in Means & Proportions
5. Hypothesis Testing:
   - Serum Cholesterol (Population Mean Test)
   - Gender (Population Proportion Test)
   - Age vs Heart Disease (Two-sample Mean Test)
   - Fasting Blood Sugar (Two-sample Proportion Test)
6. ANOVA for Resting Blood Pressure across Chest Pain categories
7. Full set of visualizations generated using R

---

## Key Visualizations

### Correlation Heatmap  
![Heatmap](https://github.com/Kartikay77/Statistical-analysis-of-heart-disease-dataset/blob/main/corrgram.png)

### Chest Pain vs Heart Disease  
![ChestPain_vs_HeartDisease](https://github.com/Kartikay77/Statistical-analysis-of-heart-disease-dataset/blob/main/cp_vs_count_hd.png)

### Gender Distribution  
![GenderStats](https://github.com/Kartikay77/Statistical-analysis-of-heart-disease-dataset/blob/main/gender_stats_barplot.png)

### Age Distribution (Healthy vs Heart Disease)
![AgeBoxplot](https://github.com/Kartikay77/Statistical-analysis-of-heart-disease-dataset/blob/main/boxplot_age.png)

### Age vs Max Heart Rate  
![MaxHR_vs_Age](https://github.com/Kartikay77/Statistical-analysis-of-heart-disease-dataset/blob/main/maxhr_vs_age.png)

### ANOVA – Residuals vs Fitted  
![ANOVA_Plot](https://github.com/Kartikay77/Statistical-analysis-of-heart-disease-dataset/blob/main/anova_plot.png)

---

## Files
- `Stat_501_Project.Rmd` — Full RMarkdown Analysis  
- `.png` files — All generated plots  
- `README.md` — Documentation  

---

## How to Run
```bash
git clone https://github.com/Kartikay77/Statistical-analysis-of-heart-disease-dataset
cd Statistical-analysis-of-heart-disease-dataset

# Open RStudio and knit the Rmd:
open Stat_501_Project.Rmd
```

---
## Insights Summary
Chest Pain type shows strong association with heart disease (Chi-square).
Age is significantly higher among heart-disease patients.
Serum Cholesterol deviates significantly from hypothesized mean.
Gender shows higher male prevalence for heart disease.
ANOVA shows Chest Pain affects RestBP distributions.

---

Dataset Source
UCI Machine Learning Repository Heart Disease Dataset
https://archive.ics.uci.edu/ml/datasets/Heart+Disease
