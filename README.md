## multiple-reg-analysis
# Multiple Regression Analysis on Factors Contributing to College Affordability

This is an extension of my Applied Regression Models Final Project using R. I also replicated the R code in Python because my college doesn't offer any Python courses in my department, and it would be a good way to learn regression techniques. I may try to replicate this code in SAS if time permits. I used R version 3.6.2 and Python version 3.6.5. Package versions from both languages can be made available upon request.  I've attached the original dataset and a data dictionary along with my R and Python files.

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

## References
**_Introduction to Regression Modeling_** by Bovas Abraham and Johannes Ledolter <br/>
**_Statistical Analysis with R For Dummies_** by Joseph Schmuller <br/>
**_R for Data Science: Import, Tidy, Transform, Visualize,	and Model Data_** by Hadley Wickham and Garrett Grolemund <br/>
https://datascience-enthusiast.com/R/ML_python_R_part1.html <br/>
https://catalog.data.gov/dataset/college-scorecard <br/>
https://www.rdocumentation.org/packages/base/versions/3.6.1/topics/any <br/>
https://www.rdocumentation.org/packages/dplyr/versions/0.5.0/topics/select_if <br/>
https://towardsdatascience.com/a-beginners-guide-to-linear-regression-in-python-with-scikit-learn-83a8f7ae2b4f <br/>
https://stackoverflow.com/questions/32827269/adding-columns-to-matrix-in-python <br/>
https://www.statsmodels.org/dev/examples/notebooks/generated/ols.html <br/>
