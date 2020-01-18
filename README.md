## multiple-reg-analysis
# Multiple Regression Analysis on Factors Contributing to College Affordability

This is an extension of my Applied Regression Models Final Project using R. I also replicated the R code in Python because my college doesn't offer any Python courses in my department, and it would be a good way to learn regression techniques. I may try to replicate this code in SAS if time permits. I used R version 3.6.2 and Python version 3.6.5. Package versions from both languages can be made available upon request.  I've attached the raw dataset along with my R and Python files.

## Background
Data was collected on multiple attributes by College Scorecard (2017-2018) for colleges across the U.S. and neighboring territories (𝑁=7112, 𝑛=790 for cleaned dataset).  The data was retrieved from data.gov, and there is a new College Scorecard 2018-2019 dataset available there now.

My research question of interest: **What are the major contributing factors (i.e. best predictors) to college affordability?**

## Methods/Results
See attached code files.

## Conclusions
-The reduced model performed well for NDSU with the coefficient matrix holding **PCTPELL** constant <br/>
-**ACTCMMID** seemed to be the best predictor of NDSU’s total cost holding all else constant <br/>
-**ADM_RATE_ALL** and **NPT4_PRIV** (set coefficient to 0 for public schools) seemed to be the worst individual predictors of NDSU’s cost <br/>
-The reduced model didn’t quite work using all our coefficients <br/>
