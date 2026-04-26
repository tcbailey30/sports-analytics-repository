## Team Wins Prediction Project ##

### Objective ###
- To predict Wins based on using MLB metrics such as Runs Scored, Runs Allowed, HR, ERA, Errors, Strikeouts, OBP, SLG, Attendance, and Payroll

### Questions to answer ###
#### Section 1 - Exploratory Data Analysis ####
1. Which stat has strongest correlation with wins?
2. Do teams that score more runs always win more?
3. How important is run prevention vs offense?
4. Has HR become more predictive over time?
5. Are expensive teams better?

#### Section 2 - Feature Engineering ####
1. Should we use Run Differential? (Runs Scored - Runs Allowed)
2. Should we use winning percentage instead of wins?
3. Should stats be normalized by games played?

#### Section 3 - Modeling ####
Using the following models:
    - Model 1 : Linear Regression
    - Model 2: Random Forest Regressor
    - Model 3: XGBoost

1. Which model predicts wins best?
2. What is MAE (average error)?
3. Which features matter most?
4. Can model predict playoff teams?

#### Section 4 - Baseball Insights ####
1. Is pitching more valuable than hitting?
2. Can low-payroll teams overperform?
3. What makes 100-win teams special?


We will use four notebooks in this project to keep workflow clean:
1. Data Cleaning
2. EDA
3. Modeling
4. Conclusions