# 🎬 What Factors Drive a Movie's Financial Success?

> **A Correlational Analysis of Budget, Genre, and Audience Reception on Movie Profitability**  
> UCSB PSTAT 100 Final Project | Collaborators: Manmeet Shergill, Jiho Shin

[📄 Click here to view the Full PDF Report](./movie_profitability.pdf)

---

## 📌 Project Overview
Using the **TMDB 5000 Movie Dataset**, this study investigates the key drivers behind film profitability (Net Profit = Revenue - Budget) and Return on Investment (ROI). We parsed complex JSON metadata, performed Exploratory Data Analysis (EDA), and conducted Pearson correlation tests and OLS regression to assess whether audience reception, marketing presence, or budget best explains commercial success.

---

## 🔍 Key Findings
* **Marketing & Reach > Audience Ratings**: Vote count ($r = 0.74$) and popularity score ($r = 0.59$) exhibit strong positive correlations with net profit, whereas audience rating (`vote_average`) showed a weak correlation ($r = 0.23$).
* **Profit vs. ROI Disconnect**: Higher budgets generate larger gross profits ($r = 0.55$), but show essentially zero correlation with ROI ($r = -0.02$). Scale does not guarantee capital efficiency.
* **Genre Trends**: 
  * **Animation** demonstrated the most consistent high returns (mean profit: $198M, median: $125M).
  * **Adventure, Fantasy, and Sci-Fi** showed high means driven primarily by extreme blockbuster outliers rather than consistent performance.

---

## 🛠 Tech Stack
* **Language & Environment**: R, RStudio, Quarto (`.qmd`)
* **Libraries**: `tidyverse` (`dplyr`, `ggplot2`), `jsonlite`, `janitor`, `corrplot`, `kableExtra`

---

## 📁 Repository Structure
* `movie_profitability.qmd`: Complete Quarto source code containing data cleaning, JSON parsing, modeling, and visualizations.
* `movie_profitability.pdf`: Final rendered PDF research paper.
* `tmdb_5000_movies.csv`: TMDB 5000 movie metadata.
