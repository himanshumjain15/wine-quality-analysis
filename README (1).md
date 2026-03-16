# Wine Quality Statistical Analysis

## Overview

This project analyzes how physicochemical properties influence wine
quality using statistical methods. The study uses the Wine Quality
dataset from the UCI Machine Learning Repository, which contains
chemical measurements and quality ratings for Portuguese Vinho Verde red
and white wines.

The objective of the project is to determine whether chemical attributes
can explain variations in wine quality and whether statistical analysis
can identify meaningful relationships in the data.

------------------------------------------------------------------------

## Objectives

This project focuses on the following research questions:

1.  Do red and white wines differ significantly in their chemical
    composition, particularly alcohol content?
2.  Can wine quality be predicted using physicochemical properties?
3.  Is there a statistically significant difference in average quality
    ratings between red and white wines?

------------------------------------------------------------------------

## Dataset

The dataset used in this analysis is the **Wine Quality Dataset** from
the UCI Machine Learning Repository.

Dataset characteristics:

-   1,599 red wine samples
-   4,898 white wine samples
-   Quality scores ranging from 0--10 based on expert evaluations

Features include:

-   Fixed acidity
-   Volatile acidity
-   Citric acid
-   Residual sugar
-   Chlorides
-   Free sulfur dioxide
-   Total sulfur dioxide
-   Density
-   pH
-   Sulphates
-   Alcohol

------------------------------------------------------------------------

## Methods

### Data Processing and Exploratory Data Analysis

-   Red and white wine datasets were combined into a single dataset.
-   A categorical variable was added to distinguish wine types.
-   Exploratory data analysis was performed to understand distributions
    and relationships between variables.
-   Visualizations such as histograms, boxplots, and correlation
    matrices were generated.

### Hypothesis Testing

A two-sample t-test was conducted to determine whether the mean alcohol
content differs between red and white wines.

Hypotheses:

H0: Mean alcohol content of red wines equals that of white wines\
H1: Mean alcohol content differs between the two wine types

The statistical test showed a significant difference in alcohol content
between red and white wines.

### Bootstrapping

Bootstrapping was used to estimate the difference in average quality
scores between wine types. This approach repeatedly resamples the
dataset to estimate the distribution of the difference in means.

------------------------------------------------------------------------

## Key Findings

-   Alcohol content is positively associated with wine quality.
-   Volatile acidity negatively affects wine ratings.
-   Red and white wines differ statistically in alcohol content.
-   White wines show slightly higher average quality scores in this
    dataset.

------------------------------------------------------------------------

## Tools and Technologies

-   R
-   R Markdown
-   Statistical methods including:
    -   Exploratory Data Analysis
    -   Correlation Analysis
    -   Two-Sample T-Test
    -   Bootstrapping

------------------------------------------------------------------------

## Repository Structure

wine-quality-analysis/

data/\
winequality-red.csv\
winequality-white.csv

notebooks/\
analysis_notebook.ipynb

report/\
Jain_Himanshu_Stats_5000_final_report.pdf

README.md

------------------------------------------------------------------------

## Future Work

Future improvements may include:

-   Applying machine learning models such as Random Forest or Gradient
    Boosting
-   Modeling nonlinear relationships between physicochemical variables
-   Addressing class imbalance in quality ratings
-   Developing predictive models for high-quality wines

------------------------------------------------------------------------

## Author

Himanshu Manish Jain\
MS Data Science\
University of Colorado Boulder
