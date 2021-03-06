# A Package for Exploratory Data Analysis

## Summary

Exploratory Data analysis is an important step in any data analysis. There are some general steps like describing the data, knowing `NA` values and plotting the distributions of the variables  which are performed to understand the data well. All these tasks require a lot of coding effort. The package tries to address this issue by providing a single function which will generate a general exploratory data analysis report. This report will contain the distribution plots of categorical and numerical variables, correlation matrix and a numerical and graphical representation to understand and identify `NA` values.

## Package positioning

The package helps in the EDA process of data analysis. There are other similar package which can be used for EDA analysis. A package which does a similar thing is [DataExplorer](https://www.rdocumentation.org/packages/DataExplorer/versions/0.8.1). The package scans and
analyzes each variable, and visualizes them with typical graphical techniques.

## Functions

1. `calc_cor`: This function will take in data frame and will plot correlation matrix of the features
2. `describe_na_values` : This function will take in data frame and will plot heat map to locate NA values in each feature and will also give a table listing number of NA values in each feature.
3. `describe_cat_var`: This function will take data frame and categorical variable names and will plot the histogram of each categorical variable
4. `describe_num_var`: This function will take data frame and numerical variable names and will plot the histogram of each numerical variable.
5. `generate_report`: This is a wrapper function which generates an EDA report by plotting graphs and tables for the numeric variables, categorical variables, NA values and correlation in a dataframe


# edar

<!-- badges: start -->

<!-- badges: end -->

The goal of edar is to conduct initial EDA for exploring data in a
dataframe.

## Installation

You can install the released version of edar from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("edar")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("UBC-MDS/edar")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(edar)
## basic example code
```
