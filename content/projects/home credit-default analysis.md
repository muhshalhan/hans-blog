---
title: "Home Credit: Comprehensive Default Risk Analysis"
date: 2023-11-18
draft: false
author: "Muhammad Shalhan Assalam"
tags:
    - Analysis
    - LightGBM
    - Banking
    - Machine Learning
    - Survival Analysis
    - Segmentation
    - Python
    - Fintech
image: /images/home credit-default analysis/main.jpg
description: ""
toc:
---

## Situation

As a Data Analyst at Home Credit, I led a comprehensive analysis to predict loan defaults. My multifaceted approach involved exploratory data analysis, customer segmentation, machine learning models, feature importance, value at risk calculation, and survival analysis to gain insights and formulate risk-banking standard recommendations to reduce the overall default rate.

### Backround
Home Credit is a credit company that mainly provide financial service for unbankable and unexperienced customer. Because of this purpose, Home Credit has huge risk exposure that affect their credit portofolio. Last year, they have booked 8% of default rate which quite large for credit industry.

With global inflation risk and VUCA conditions in the global economy, management wants to take this issue seriously. They asked the data team to develop a machine learning model using historical credit application and transaction data, to predict each customer's likelihood of defaulting this year. From this prediction, we conducted further analysis using value at risk and survival analysis as risk banking standard assessments to effectively treat each segment. So, our model can produce high-quality insights to address the default rate problem.

### Problem Definition
How to predict and maintain for a robust 6% of credit default rate at the end of the year?

### Objective
The objectives of this analysis were to:

1. Perform exploratory data analysis on historical credit application and transaction data
2. Segment customers into groups based on key characteristics
3. Develop machine learning models by conduct feature engineering, hyperparameter tuning, and cross validation
4. Obtain credti default probability from Light GBM model with target 6% default rate by year
5. Identify key indicators in default prediction using feature importance
6. Calculate value at risk for each customer segment to quantify potential losses
7. Conduct survival analysis to determine expected time to default for segments
8. Formulate data-driven recommendations and insights to reduce overall default rate
9. Optimize lending decisions and credit limits/pricing based on customer risk profiles

## Task & Action
| Task | Action | Reason |
|-|-|-|  
| Exploratory Data Analysis | Visualize distributions, correlations, missing values etc. on historical application and transaction data | Understand data and identify relevant features for modeling |
| Customer Segmentation | Group customers using clustering algorithms based on attributes like demographics, financial history etc. | Divide customers into homogeneous segments for targeted analysis | 
| Build Prediction Models | Engineer features, tune hyperparameters, use cross-validation etc. to create ML models predicting default | Output default probabilities for each customer |
| Model Evaluation | Assess model performance using accuracy, AUC, confusion matrix etc. | Determine best model for predicting likelihood of default |
| Feature Importance | Analyze feature importance from model | Identify key default indicators for monitoring |
| Value at Risk Analysis | Use VaR method on customer segments | Quantify potential losses for risk management | 
| Survival Analysis | Estimate survival curves and hazard rates for segments | Understand expected default timing for segments |
| Recommendations | Derive data-driven recommendations from analysis | Reduce overall default rate |
| Model Implementation | Integrate model into lending decisions and credit limit/pricing rules | Operationalize model predictions to optimize business impact |

## Result - Slide Deck

From this project, I've utilized 6 dataset with 400K+ agregated rows and 600+ features from total 25M+ data points. Due to complexity of data and features, I've applied LGBM to my model as their capability to handle large dataset and I've performed hyperparameter tuning with bayesian search, 5-step k-fold validation with 100 early stopping to prevent overfitting model. Thanks to Aguiar and team from kaggle, I've used their LGBM preset to save a lot of time and computational source. From my model, I've obtain final CV score 0.8 but their tend to overfitting with train score 92-95% because unbalanced class. However, this model is still highly effective for several reasons:
1. An 0.8 AUC score considerable high and enough to differentiates class
2. Credit default is complex real word scenario and it’s acceptable and commont to adopting overfit model
3. We’ve applied robust mitigation procedure to reduce overfit, like hyperparameter tuning, early stop, and k-fold validation
4. We are concern with data reliability and we don’t take any synthetic balancing method to obtain applicable and valid insights.
5. This model actually adapted from 7th kaggle champion on highest LB and CV (0.8)

If you excited with my project, you can read the full version below

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vROLKtRuyL5MOJbbjQOsCB9D_SNf-U8PChgStB4cZ3G9Xnn2KGPxPdMH4z0GDyYaAXM2UnDwtwNpS1T/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="490" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


---

### Attachments

<a href="https://www.kaggle.com/competitions/home-credit-default-risk/data" target="_blank">>> Dataset Link <<</a> | <a href="https://colab.research.google.com/drive/10frG3X3ltdYGdZ3ckGwdz_J89AMg6wIZ?authuser=0#scrollTo=2Emsf1P8-eGR&uniqifier=1" target="_blank">>> Colab Link <<</a>

---

I'm grateful you took the time to explore my portfolio site and view my work. Your interest means a lot. 

Feel free to provide any feedback or ask questions - I welcome your thoughts. Thank you again for checking out my projects and considering my skills. I appreciate you taking the time to do so.

<a href="https://www.linkedin.com/in/muhshalhan/" target="_blank">>> Let's get in touch on LinkedIn! <<</a>