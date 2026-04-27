# MLB Payroll vs Wins Analysis

## Project Overview

This project analyzes whether spending more money on player salaries leads to more wins in Major League Baseball.

Using the Lahman Baseball Database, I combined team payroll data with team performance data to explore:

- Does higher payroll produce more wins?
- Which teams were most efficient with spending?
- Which teams underperformed despite large payrolls?
- Can payroll predict wins using machine learning?

This project demonstrates skills in sports analytics, data cleaning, exploratory data analysis, visualization, and predictive modeling.

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git / GitHub

---

## Data Sources

Lahman Baseball Database:

- Salaries.csv
- Teams.csv

---

## Project Workflow

1. Imported and cleaned raw datasets
2. Aggregated payroll by team and season
3. Merged payroll with team wins/losses
4. Created efficiency metrics such as cost per win
5. Built visualizations to analyze trends
6. Created linear regression model to predict wins from payroll
7. Identified overperforming and underperforming teams

---

## Key Findings

- Payroll has a positive relationship with wins, but not a perfect one.
- High payroll teams often win more games on average.
- Several lower payroll teams significantly outperformed expectations.
- Spending money helps, but smart roster construction matters.

---

## Visuals

### Payroll vs Wins
### Actual vs Predicted Wins
---

## Machine Learning Results

Linear Regression was used to predict wins from payroll.

Metrics included:

- MAE
- RMSE
- R² Score

This showed payroll explains part of team success, but many other variables matter.

---

## Folder Structure

sports-analytics-portfolio/
│── data/
│── notebooks/
│── visuals/
│── README.md

---

## Future Improvements

- Adjust salaries for inflation
- Add postseason success analysis
- Compare payroll efficiency by decade
- Add player WAR statistics
- Use Random Forest / XGBoost models

---

## Author

Created by Timothy Bailey as part of a Sports Analytics Portfolio.