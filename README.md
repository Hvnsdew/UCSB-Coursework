# 📊 UCSB Data Science & Statistical Coursework

This repository contains academic data science and statistical analysis projects completed at the University of California, Santa Barbara (UCSB). Each project demonstrates applied statistical modeling, data cleaning pipelines, and reproducible reporting using R and Quarto.

---

## 📌 Featured Projects

### 1. [Socioeconomic Disparities & Family Poverty Analysis](./Project1-US-Socioeconomic-Analysis/)
* **Coursework**: UCSB PSTAT 100 Mid-Quarter Project | Author: Jiho Shin
* **Focus**: Relational Multi-table Joins, Demographic Stratification, and Multiple Linear Regression.
* **Dataset**: Based on the U.S. Census Bureau Current Population Survey (CPS) 2024 Annual Social and Economic Supplement (ASEC).
* **Key Findings**:
  * Harmonized and integrated three microdata levels (Household, Family, and FIPS geographic codes).
  * Evaluated regional income divides across the Northeast, Midwest, South, and West.
  * Estimated multiple regression models showing statistically significant negative effects of family size (`FPERSONS`) and specific regional baselines on the income-to-poverty ratio.
* **Tech Stack**: R, Quarto, `tidyverse`, `sjPlot`, `scales`
* **Artifacts**: [📄 View Full PDF Report](./Project1-US-Socioeconomic-Analysis/Mid_Quarter_Project_Report.pdf) | [Source Code](./Project1-US-Socioeconomic-Analysis/Mid_Quarter_Project_Report.qmd)

---

### 2. [What Factors Drive a Movie's Financial Success?](./Project2-Movie-Profitability/)
* **Coursework**: UCSB PSTAT 100 Final Project | Collaborators: Manmeet Shergill, Jiho Shin
* **Focus**: Exploratory Data Analysis, Non-linear Patterns, Pearson Correlation, and OLS Regression.
* **Dataset**: TMDB 5000 Movie Dataset (Kaggle).
* **Key Findings**: 
  * Marketing reach and volume of engagement (`vote_count`: $r = 0.74$, `popularity`: $r = 0.59$) correlate significantly more strongly with net profit than raw audience rating (`vote_average`: $r = 0.23$).
  * Production budget scales gross profit ($r = 0.55$) but shows essentially no linear relationship with capital return efficiency / ROI ($r = -0.02$).
  * **Animation** demonstrated the most consistent high median return, whereas rare blockbuster outliers drove Adventure and Sci-Fi returns.
* **Tech Stack**: R, Quarto, `tidyverse` (`dplyr`, `ggplot2`), `jsonlite`, `janitor`, `corrplot`
* **Artifacts**: [📄 View Full PDF Report](./Project2-Movie-Profitability/movie_profitability.pdf) | [Source Code](./Project2-Movie-Profitability/movie_profitability.qmd)

---

## 🔒 Data Access & Academic Integrity Note
* **Public Data**: The TMDB 5000 dataset in Project 2 is sourced from Kaggle under open database licensing.
* **Restricted Data**: Datasets for Project 1 (`hhpub24-2.csv`, `ffpub24-1.csv`, `fips_abbrev-1.csv`) are proprietary course materials and are intentionally excluded from this repository in accordance with institutional data policies and UCSB Academic Integrity guidelines.
* All code and reports are shared strictly for educational portfolio presentation and code review.
