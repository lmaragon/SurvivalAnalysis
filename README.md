# SurvivalAnalysis

## Author
Luis Aragon.
Completed on December 1st, 2018

## View Final Product
To view the final project, refer to the SurvivalAnalysisProject.pdf file in the repository.

## Description
This data set is a Drug Treatment Dataset from *Applied Survival Analysis: Regression Modeling of Time to Event Data* by David Hosmer and Stanley Lemeshow. The data covers the time since a patient was admitted into a treatment program until they relapsed (failure time). For the censored data, a 1 is given if they relapsed (returned to drugs), and a 0 if they were censored. The rest of the columns are interesting variables which we can explore. By looking at the data, we see it contains 575 records. This dataset originally contained 628 records, but now has 575 with no missing values. Each row refers to one patient. Variables include AGE (age at enrollment), BECK (continuous Beck Depression Score from 0-63), TREAT (short vs long treatment), and SITE (treatment site). The aim for modelling this data is to see the time to relapse for these patients and the probability of relapsing over time. The researchers of the study collected many variables, which can be used to model and predict relapse (failure) probabilities throughout time. The researchers and creators of this study intentionally randomized the treatment variable, TREAT, because they wanted to know if there was an effect of treatment length on relapse time of the patients. This is the variable I will be analyzing.

## Research Question

Does the treatment length have an effect on relapse time?

## TOOLS
RStudio: R and RMarkdown
