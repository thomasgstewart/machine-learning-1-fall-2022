# Framingham Heart Study

Read the history of the [Framingham Heart Study](https://www.framinghamheartstudy.org/fhs-about/).

In this assignment, you will fit regression models predicting log serum cholesterol from BMI, age, and sex.

The data is avaiable with the command

```
d1 <- read.csv("http://hbiostat.org/data/repo/2.20.Framingham.csv")
# Note for the sex variable: 1 = Male, 2 = Female
```

1. Specify a model of log serum cholesterol (`scl`) with the three predictors.  Allow the model to capture nonlinear relationships and sex-specific relationships.

2. Fit the model with MLE and Bayesian methods.  Specify any priors that you use.

3. Generate partial effect plots from one of the models.  In the plot, label the predicted median serum cholesterol for a 48 year old female with BMI of 28. 

### Submission instructions

1.  Within your course repo, create a folder called `02A-framingham`
1.  Within the folder, create an .html solution file with the name
    `writeup`