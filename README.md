# STAT 151A - Linear Modeling: Theory and Applications

- Description: This is a course on linear models as well as generalized linear models and their application. Topics include linear regression and modeling, visualization and diagnostics, confidence intervals and hypothesis, analysis of variance, dealing with large number of predictors, and generalized linear models.
- Instructor: Gaston Sanchez
- Lecture: 2 days p/week; 1.5 hours each day
- Up to 2 midterm exams
- One final exam
- Primary notes/texts:
    + Prof. Sanchez's notes
- Secondary texts: 
    + Applied Regression Analysis and Generalized Linear Models (by John Fox)
    

-----

## 1. Introduction

:card_index: __ABOUT__: By the end of this introductory module, you will be able to:

- Define what a linear model is (in what sense a model is said to be linear)
- Describe the high-level intuition of regression (and the regression function)


:book: __READING__: 
- Preliminary concepts

:pencil2: __TOPICS__:
+ __Preliminary Concepts__
	- Intuition of regression
	- Meaning of the term "linear"
	- Geometric duality of a data set
	- Review of orthogonal projections


-----

## 2. Simple Linear Regression (SLR)

:card_index: __ABOUT__: In this week, we introduce the descriptive aspects of a __Simple Linear Regression__ model. This involves postponing the discussion of inferential aspects for later. In particular, we will focus on the method of (Ordinary) Least Squares to obtain the estimated coefficients of a simple linear model. Likewise, we'll discuss the geometric aspects of OLS, and understand how the Gauss-Markov assumptions wrap a linear model with a first layer of "soft" statistical assumptions.


:book: __READING__: 
- Geometry of simple regression
- Gauss-Markov assumptions in simple regression


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

:card_index: __ABOUT__: This week, we introduce the model-fitting aspects of __Multiple Linear Regression__. Like we did in the previous module, we postpone the discussion of the inferential aspects for later. We'll keep our focus on the method of (Ordinary) Least Squares to obtain the coefficients of a multiple linear model. Likewise, we'll continue to study the geometric aspects of OLS, and understand how the Gauss-Markov assumptions wrap a linear model with a first layer of "soft" statistical assumptions.


:book: __READING__: 
- Geometry of multiple regression
- Gauss-Markov assumptions in multiple regression


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

:card_index: __ABOUT__: In this module, we begin the introduction of the Normal Theory (i.e. so-called Normality assumptions) for linear regression models. This involves assuming that random error terms are Normally distributed, which is a requirement in order to make inferences (e.g. confidence intervals, hypothesis tests) within regression modeling.

We'll study how the Normality assumptions wrap a linear model with another layer of theoretical assumptions (we like to think of this as a second layer of "hard" statistical assumptions). This involves deriving Maximum Likelihood (ML) estimators, and also studying the distributions of the estimated regression quantities (e.g. coefficients, fitted values, residuals, sums of squares, etc).

:book: __READING__: 
- Normality assumptions in simple regression
- Normality assumptions in multiple regression


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

