# Experimental Design and Causality

This repository contains my coursework and hands-on projects for **Experimental Design and Causality**. The goal is to apply statistical methods in Python to better understand causal relationships, experimental design, and data-driven decision making.

## Topics Covered

The repository will be updated throughout the course and will include topics such as:

- Linear Regression
- Regression Coefficients and Statistical Significance
- Matching Methods
- Nearest Neighbor Matching
- Radius-Based Matching
- Treatment Effect Estimation
- Experimental Design
- Causal Inference

## Week 1 — Linear Regression and Matching

In Week 1, I worked with two datasets to explore regression analysis and matching methods.

### Part 1: Linear Regression

A multiple linear regression model was used to predict an outcome variable `Y` using `X1`, `X2`, and `X3`.

The analysis included:

- Exploring and validating the dataset
- Fitting an OLS multiple linear regression model
- Interpreting regression coefficients
- Comparing simple and multiple regression coefficients
- Evaluating statistical significance using t-statistics
- Understanding how controlling for other variables changes coefficient estimates

### Part 2: Matching

Matching techniques were used to compare treated (`X = 1`) and control (`X = 0`) observations based on the variable `Z`.

Two approaches were explored:

**Nearest Neighbor Matching**
- Identified the closest control observation for each treated observation
- Calculated matching distances
- Constructed a matched control sample
- Estimated the treatment effect using matched observations

**Radius-Based Matching**
- Identified all control observations within a specified distance of each treated observation
- Examined repeated matches and duplicate observations
- Calculated the average outcome within each matched neighborhood
- Estimated the treatment effect using the matched groups

## Tools

- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## Repository Structure

- `week1_linear_regression_and_matching-week1.ipynb` — Week 1 regression and matching analysis
- Additional notebooks will be added as the course progresses.

## Purpose

This repository documents my progress in applying statistical and causal inference methods through practical Python exercises. It serves as both a learning record and a portfolio of my work in experimental design and causal analysis.
