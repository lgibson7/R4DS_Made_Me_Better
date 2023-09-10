# Practicality of Using Transformations in Multiple Linear Regression

In our previous research, [Gender Wage Inequality in STEM](https://github.com/lgibson7/Gender-Wage-Inequality-in-STEM), my colleagues and I used multiple linear regression (MLR) to explore the relationship between gender demographics and median salary of STEM major categories. Our final model used the inverse transformation of the response variable to improve the model fit. Transforming response (and/or explanatory) variables, common practice among statisticians, can lead to a better fitting model, but these models are not easily understood by the average person. 

# Research Goals

In this project, I compared the multiple linear regression model with the inverse transformation dependent response variable, $Median^{-1}$, from my previous project to a comparable model without an inverse transformation dependent response variable. My goal was to see how much prediction power is lost by not using a transformed response variable to fit a MLR model, and whether it is worth the inability to easily explain your model when using a transformed response variable.


# Dataset Used

To address this problem, I used a subset of the College Majors dataset from FiveThirthyEight, found here: https://github.com/fivethirtyeight/data/blob/master/college-majors/women-stem.csv

# Tools Used

* Packages: tidyverse, ggpubr, easystats, lindia, ggstatsplot
* Statistical Tests & Analyses: Box-Cox, Step-wise selection, Model Diagnostics
