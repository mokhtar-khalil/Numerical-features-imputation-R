# Numerical-features-imputation-R

## Project Name: Imputation of Missing Values in Agricultural Land Usage Data

## Description:
This project focuses on imputing missing values in the variable "F6," which represents the number of hectares of agricultural land used by households that they do not own. The aim is to estimate and fill in the missing values using different imputation methods.

## Methods Used:

MICE (Multivariate Imputation by Chained Equations): The MICE package is used to impute missing values in the dataset. It performs multiple imputations by creating several plausible values for each missing entry based on the observed data patterns.
k-NN (k-Nearest Neighbors): The k-NN imputation method is employed to estimate missing values by finding the nearest neighbors to the missing entries based on other available variables. The k nearest neighbors are used to compute the imputed value.
Hot Deck: The hot deck imputation technique is used to fill in missing values by matching each missing entry with a similar observed entry in terms of relevant variables.
Evaluation:
The imputed values from each method are evaluated by comparing the density plots of the original non-missing values with the imputed values. The density plots provide a visual comparison to assess the accuracy of the imputation methods.

## Acknowledgments:
I would like to acknowledge the developers of the MICE, kNNImputation, and hotdeck packages for their valuable contributions to the field of missing data imputation in R.
