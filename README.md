# STAT 151A - Linear Modeling: Theory and Applications

- Description: This is a course on linear models as well as generalized linear models and their application. Topics include linear regression and modeling, visualization and diagnostics, confidence intervals and hypothesis, analysis of variance, dealing with large number of predictors, and generalized linear models.

- Instructor: Gaston Sanchez

- Lecture: 2 days p/week; 1.5 hours each day

- Exams: Up to 2 midterm exams, and final test

- Notes and texts:
    + Prof. Sanchez's notes
    + Applied Regression Analysis and Generalized Linear Models (by John Fox)

- Prerequisites: Statistical and Probability Theory, as well as Linear Algebra. It owuld also be nice to have some familiarity with R.


-----

## 1. Introduction

:card_index: __ABOUT__: By the end of this introductory module, you will be able to:

- Define what a linear model is (in what sense a model is said to be linear)
- Describe the high-level intuition of regression (and the regression function)

<br>

:book: __READING__:

- Chapters 1 and 4
- Preliminary concepts

<br>

:pencil2: __TOPICS__:

+ __Preliminary Concepts__
	- Intuition of regression
	- Meaning of the term "linear"
	- Geometric duality of a data set
	- Review of orthogonal projections


-----

## 2. Simple Linear Regression (SLR)

:card_index: __ABOUT__: 

In this week, we introduce the descriptive aspects of a __Simple Linear Regression__ model. This involves postponing the discussion of inferential aspects for later. In particular, we focus on the method of (Ordinary) Least Squares to obtain the estimated coefficients of a simple linear model. Likewise, we discuss the geometric aspects of OLS, and understand how the Gauss-Markov assumptions wrap a linear model with a first layer of "soft" statistical assumptions.

<br>

:book: __READING__:

- Chapters 5.1 and 10.1
- Geometry of simple regression
- Gauss-Markov assumptions in simple regression

<br>

:pencil2: __TOPICS__:

+ __Simple Linear Regression (SLR)__
  - Residual Sum of Squares
  - Least Squares estimates
  - Geometry of simple OLS
  - Analysis of Variance decomposition
+ __SLR under GM assumptions__
  - Gauss Markov Assumptions
  - Properties of OLS coefficients
  - Properties of OLS estimates
  - Estimate of standard deviation (sigma)
  - Gauss-Markov Theorem


-----

## 3. Multiple Linear Regression (MLR)

:card_index: __ABOUT__: 

This week, we introduce the model-fitting aspects of __Multiple Linear Regression__. Like we did in the previous module, we postpone the discussion of the inferential aspects for later. We'll keep our focus on the method of (Ordinary) Least Squares to obtain the coefficients of a multiple linear model. Likewise, we'll continue to study the geometric aspects of OLS, and understand how the Gauss-Markov assumptions wrap a linear model with a first layer of "soft" statistical assumptions.


<br>

:book: __READING__:

- Chapters 5.2 and 10.2 and 10.33
- Geometry of multiple regression
- Gauss-Markov assumptions in multiple regression

<br>

:pencil2: __TOPICS__:

+ __Multiple Linear Regression (MLR)__
  - Introduction to Mulriple Regression
  - Least Squares estimates
  - Geometry of simple OLS
+ __SLR under GM assumptions__
  - Properties of OLS coefficients
  - Properties of OLS estimates (y-hat and residuals)
  - Estimate of variance
  - Gauss-Markov Theorem


-----

## 4. Normality Assumptions in Linear Regression

:card_index: __ABOUT__: 

In this module, we begin the introduction of the Normal Theory (i.e. so-called Normality assumptions) for linear regression models. This involves assuming that random error terms are Normally distributed, which is a requirement in order to make inferences (e.g. confidence intervals, hypothesis tests) within regression modeling.

We study how the Normality assumptions wrap a linear model with another layer of theoretical assumptions (we like to think of this as a second layer of "hard" statistical assumptions). This involves deriving Maximum Likelihood (ML) estimators, and also studying the distributions of the estimated regression quantities (e.g. coefficients, fitted values, residuals, sums of squares, etc).

<br>

:book: __READING__:

- Chapter 6
- Normality assumptions in simple regression
- Normality assumptions in multiple regression

<br>

:pencil2: __TOPICS__:

+ __Normality assumptions in SLR__
  - Normality assumptions
  - Maximum Likelihood estimators
  - Distributions of estimators
  - Distributions of sum of squares
+ __Normality assumptions in MLR__
  - Multivariate Normal distribution
  - Distributions of estimators
  - Distributions of sum of squares


-----

## 5. Inference in Linear Regression Models

:card_index: __ABOUT__: 

After reviewing the normality assumptions in regression models and how they affect the distributions of various estimates, we move onto the inferential aspects. In this module we describe how to construct confidence intervals and how to make hypothesis tests.

<br>

:book: __READING__:

- Chapter 6
- Confidence Intervals in regression models
- Hypothesis Tests in regression models

<br>

:pencil2: __TOPICS__:

+ __Confidence Intervals__
  - Confidence intervals for regression coefficients
  - Meaning of "predictions"
  - Intervals for predictions
+ __Hypothesis Tests__
  - Test for a single predictor
  - F-test for multiple predictors
  - F-test and anova test


-----

## 6. Dummy Variables and ANOVA

:card_index: __ABOUT__: 

So far we've studied linear regression models under the implicit assumption that both the response and the predictors are quantitative variables. However, we still need to study what to do when we have one or more predictors that are qualitative (i.e. categorical).

<br>

:book: __READING__:

- Chapters 7 and 8
- Dummy Variables
- ANOVA

<br>

:pencil2: __TOPICS__:

+ __Dummy Variables__
  - Dummy Regressors for categorical variables
  - The use of dummy (i.e. binary) indicator variables
  - Various types of encoding for categorical variables
+ __ANOVA__
  - Introduction to ANOVA
  - One-way anova: constraints, estimates, and dispersion
  - Anova test


-----

## 7. Residual Analysis and Diagnostic Tools

:card_index: __ABOUT__: 

The estimation of and inference from the regression model depend on several assumptions. These assumptions should be checked using regression diagnostics before using the model in earnest. This week, we cover diagnostic tools for assessing the validity of assumptions about the model specification, the error terms, and issues with unusual and influential observations.

<br>

:book: __READING__:

- Chapters 11 and 12
- Residual Analysis (part 1)
- Residual Analysis (part 2)

<br>

:pencil2: __TOPICS__:

+ __Residual Analysis (part 1)__
  - Problems in regression analysis
  - Residuals and Leverages
  - Types of residuals
  - Basic residual plots
+ __Residual Analysis (part 2)__
  - Detecting heteroscedasticity
  - Detecting non-normality
  - Detecting unusual observations
  - Detecting influential observations


-----

## 8. Multicollinearity

:card_index: __ABOUT__: 

Previously, we mentioned that one class of problematic issues in regression has to do with the __Rank__ assumption of the design matrix __X__ (full rank). This week, we discuss in what way not having a full rank matrix __X__ affects the estimated regression quantities. More specifically, we'll study the common issue of dealing with multicollinearity.

<br>

:book: __READING__:

- Chapter 13
- The Sum-of-Squares-and-Cross-Products (SSCP) matrix __X'X__
- Multicollinearity

<br>

:pencil2: __TOPICS__:

+ __Review of the SSCP matrix__
  - The Sum-of-Squares-and-Cross-Products (SSCP) matrix
  - SSCP and friends
  - Notion and measures of multidimensional scatter
  - Eigenstructure of the SSCP matrix
+ __Multicollinearity__
  - What is multicollinearity
  - Examples of multicollinearity
  - Variance Inflation Fator (VIF)
  - Singular Value Decomposition (SVD) and multicollinearity


-----

## 9. Dealing with Multicollinearity

:card_index: __ABOUT__: 

In this module, we continue the discussion about multicollinearity. More specifically, we describe two methods, Principal Components Regression (PCR) and Ridge Regression (RR), that allow us to overcome some of the obstacles posed when dealing with multicollinearity.

<br>

:book: __READING__:

- Chapter 13.1 and 13.2.3
- Principal Components Analysis (PCA)
- Ridge Regression

<br>

:pencil2: __TOPICS__:

+ __Use of PCA to deal with multicollinearity__
  - Crash introduction to Principal Components Analysis
  - PCA and EVD
  - Geometry of PCA
  - Use of PCA for regression analysis
+ __Ridge Regression__
  - Introduction to Ridge Regression
  - Mean-Square-Error (MSE) in Ridge Regression
  - Geometry of Ridge Regression
  - Solution of Ridge Regression


-----

## 10. Variable Selection and Model Building

:card_index: __ABOUT__: 

In this module, we go over common methods for selecting variables, comparing models of different sizes (i.e. different number of predictors), and choosing the "best" model.

<br>

:book: __READING__:

- Chapter 22.1
- Model Choice Criteria

<br>

:pencil2: __TOPICS__:

+ __Model Selection__
  - Introduction to model selection
  - Predictive performance
  - Limitations of _R2_ for comparing models of different number of predictors
+ __Model Comparison Criteria__
  - Adjusted R-squared
  - Mallows's _Cp_
  - Akaike Information Criterion (AIC)
  - Bayesian Information Criterion (BIC)


-----

## 11. Introduction to Logistic Regression

:card_index: __ABOUT__: 

In this module, we transition into the so-called framework of Generalized Linear Models (GLM). Specifically, we start with regression models to predict a (binary) categorical predictor using the "plain vanilla" logistic regression model.

<br>

:book: __READING__:

- Chapter 14.1
- Logistic Regression
- Logistic Regression toy example

<br>

:pencil2: __TOPICS__:

+ __Logistic Regression__
  - Limitations of a linear model when applied on a binary response variable
  - Core idea to formulate a binary regression model with a logistic function
  - The Logistic regression model
+ __Logistic Regression Example__
  - Coronary Heart Disease (chd) data
  - Fitting a logistic regression model
  - Interpretation of regression coefficients


-----

## 12. Estimation in Logistic Regression

:card_index: __ABOUT__: 

In this week, we focus on the estimation of logistic regression models. The estimation criterion is based on maximum likelihood, which unfortunately cannot be solved analytically. Instead, we need to use numerical methods such as Newton's method (aka Newton-Raphson's method). This is the method behind what is perhaps the most common algorithm to estimate logistic regression models, namely: IWLS "Iterative Weighted Least Squares" (aka Iterative Re-weighted Least Squares, IRLS).

<br>

:book: __READING__:

- Chapter 14.1
- Estimation of Logistic Regression

<br>

:pencil2: __TOPICS__:

+ __Maximum Likelihood estimation in Logistic Regression__
  - Derivation of the (log)likelihood of a binary logistic regression model
  - Limitation for maximizing log-likelihood analytically
  - Estimation via numerical optimization methods (e.g. Newton's method)
  - Review of Newton's method
+ __Numerical estimation in Logistic Regression__
  - Newton's method to estimate a logistic regression model
  - Iterative Weighted Least Squares (IWLS) algorithm


-----

## 13. Poisson Regression

:card_index: __ABOUT__: 

This week we briefly describe poisson regression, and the theoretical framework of Generalized Linear Models (GLM). Much of what we've discussed about logistic regression applies to poisson regression, and to other members of GLM.

<br>

:book: __READING__:

- Chapter 15
- Introduction to Poisson Regression
- GLM Framework

<br>

:pencil2: __TOPICS__:

+ __Poisson Regression__
  - Derivation of the (log)likelihood of poisson regression model
  - Limitation for maximizing log-likelihood analytically
  - Estimation via numerical optimization methods (e.g. Newton's method)
  - Review of Newton's method
+ __GLM Framework__
  - Main components of a GLM (random component, linear predictor, and link function)
  - Link functions, and their inverses, for linear regression, poisson regression, and logistic regression
  - R functions `glm()` and their `summary()` outputs


