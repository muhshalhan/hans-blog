---
title: "RevoBank Fintech Analysis | Part 3: Propensity Modelling"
date: 2023-09-24
draft: false
author: "Muhammad Shalhan Assalam"
tags:
    - Analysis
    - Propensity Modelling
    - Logit Regression
    - Machine Learning
    - Python
    - Fintech
image: /images/revobank-analysis/main.jpg
description: ""
toc:
---

## Situation
This the last part of RevoBank analysis, we develop machine learning with propensity modelling using logit regression.

As a Data Analyst at RevoBank, I developed a propensity model to predict customers likely to adopt the new PayLater installment feature for a targeted promotion campaign.

### Backround
RevoBank launched a 3-month pilot for a PayLater installment feature on RevoShop transactions. The pilot demonstrated potential to increase credit card usage. To further boost activation, RevoBank proposed Project Contact - contacting customers to offer rewards for trying PayLater.

However, contacting all customers would be costly. RevoBank needed a targeted way to identify the highest potential customers worth contacting. By developing a propensity model using historical transaction data, I could predict each customer's likelihood of activating PayLater if offered. This would enable RevoBank to only contact the most promising customers, saving costs while still driving sign-ups. My data-driven model provides the targeting capability needed to optimize Project Contact for maximum return.

### Problem Definition
The problem was that RevoBank seeking a targeted way to identify customers likely to activate PayLater when contacted. A propensity model was needed.

### Objective
The objectives of this analysis were to:

1. Engineer features from historical transaction data, excluding future info
2. Build a classification model to predict likelihood of PayLater activation
3. Evaluate model accuracy in identifying high potential customers
4. Rank customers by predicted activation probability
5. Identify top customers to target for Project Contact promotion
6. Enable data-backed optimization of outreach for higher ROI

## Task & Action
| Task | Action | Reason |
|-|-|-|
| Review data dictionary | Understood dataset contents, identified join keys | Prepared datasets for feature engineering |
| Define model target variable | PayLater activation during pilot period as positive label | Aligned modeling goal to business objective |
| Feature engineering | Created features from historical data, excluded future info | Input relevant info to model while avoiding leakage |
| Create train/test split | Made separate datasets for training and evaluation | Assessed model generalizability | 
| Check correlations | Removed highly correlated variables | Avoided model overfit |
| Check class imbalance |Verified balance of positive/negative classes | Awareness of data distributions | 
| Build logit model | Created model predicting target variable using logit regression | Propensity modeling approach |
| Evaluate model performance | Assessed accuracy, confusion matrix, decile analysis, ROC, and K-S test  | Determined model suitability for goal |
| Feature Importance | Show feature importance from selected features in logit model | This is will help RevoBank to identify which factor most important to predict paylater user |
| Rank customers | Scored customers by predicted activation probability | Enabled selective targeting |
| Apply Benefit Cost Analysis | Chose top 30K customers from ranked list to BCA workspace | Estimate benefit to cost ratio from 30K potential customer to help RevoBank optimize their marketing acquisition cost |

## Result - Slide Deck

From this project, I've got 72% accuracy with 61%-62% ROC score, and K-S test 48.33. This model have a lot of improvement due to condition of data. I've already improved feature engineering process, so the overall model performance can slightly better than actual performance (key answer)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQg9Kwjd49R5GL4mryY-4fsXIJz5WyqXGM30eaunvtiRbpslcZktuANPvzf8-Nkx_VrQ8A84XyZl-iy/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="490" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

---

### Attachments

<a href="https://drive.google.com/file/d/1bwpWSicFoFt1huv2QBIgdKLxVlLelaqJ/view?usp=drive_link" target="_blank">>> Dataset Link <<</a> | <a href="https://docs.google.com/spreadsheets/d/1XjQ1lTtFOMRSr_EisXxnM6EJYu2Y0_zt/edit?usp=sharing&ouid=113457939531194487813&rtpof=true&sd=true" target="_blank">>> Data Dictionary Link <<</a> | <a href="https://docs.google.com/spreadsheets/d/1oHPAsBXDuJXVRhiHpjjMf8QDhT-eX3-f/edit?usp=drive_link&ouid=113457939531194487813&rtpof=true&sd=true" target="_blank">>> Pilot Data Link <<</a> | <a href="https://docs.google.com/spreadsheets/d/1TTDUqFOvudm_PDsfY0JcAnxKwqPXo0XHYgHOcF0bZQw/edit?usp=sharing" target="_blank">>> BCA Spreadsheet Link <<</a> | <a href="https://colab.research.google.com/drive/1MZXUSuvDUf2NA1Irgd2YixA4q40PbT59?usp=sharing" target="_blank">>> Colab Link <<</a>

---

I'm grateful you took the time to explore my portfolio site and view my work. Your interest means a lot. 

Feel free to provide any feedback or ask questions - I welcome your thoughts. Thank you again for checking out my projects and considering my skills. I appreciate you taking the time to do so.

<a href="https://www.linkedin.com/in/muhammad-shalhan-assalam-b42973200/" target="_blank">>> Let's get in touch on LinkedIn! <<</a>