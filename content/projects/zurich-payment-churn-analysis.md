---
title: "Zurich Payment and Churn Analysis"
date: 2024-01-11
draft: false
author: "Muhammad Shalhan Assalam"
tags:
    - Churn
    - Payment
    - Analysis
    - Machine Learning
    - Segmentation
    - Risk Analysis
    - Insurance
image: /images/zurich-marketing-campaign-analysis/main.jpg
description: ""
toc:
---

## Situation

This is my project during my internship at Zurich Insurance. In this project, Zurich's product team wanted to evaluate their payment performance from last 8 month (January - August 2023). During the 8-month, the product team had gained 380 customers consist of 350 ZLF and 30 ZLP customers. These customer has generated premiums of Rp.444,4M with a total of 979 payments. However, there were 58 churned customer (15.2%) and 414 late payment, with 405 late payments during the grace period and 9 late payments after the grace period.

The product team believed that late of payment behavior affecting high churn rate at 15%, as late payment on grace period increased over time with 60% late payment ratio, they needed the help of a Data Analyst to uncover payment pattern and identify which features most contributing to high churn rate over the past 8 months.

> DISCLAIMER: The data provided is a representation of the original data which amount have been adjusted.

### Backround

Zurich is a leading insurance provider serving its customers in both local and global markets. Currently, Zurich is developing their new product called Ziaga Life Flexy (ZLF). ZLF is a life insurance product that provides lifelong protection. During the coverage period, the designated family members as Beneficiaries will receive the sum insured in the event of the insured's death.

Zurich introducing their Ziaga Life Flexy as insurance product that provides lifetime protection (or up to 99 years). Within the protection period, the family designated as beneficiaries (heirs) can get up to Rp3 billion if you experience the risk of death. The cost of insurance (premium) is affordable starting from Rp20 thousand per month. In this case, you act as a Policyholder (insurance buyer), Insured (insured person), and Premium Payer (person who pays the insurance fee).


### Problem Definition

How to identify late on payment pattern and behavior in order to reduce churn rate under 10% by the end of 2023?

### Objective

The objective of this project was <b> to identify payment behavior pattern with churn rate analysist from last 8 months </b>. The goal was to <u> generate data-driven recommendation </u> to <b> improve payment performance and decreasing churn rate with risk management strategies</b>.

## Task & Action
| Task | Action | Reason |
|-|-|-|
| Data Cleaning | Check for missing values, duplicates, outliers, inconsistencies, and formatting issues in the data | Cleaning the data is an essential first step before analysis to ensure data quality and accuracy of insights |
| EDA/EDV with Tableau | Visualize payment performance and churn customers, such as payment period, payment method, installment amounts, late payment, etc | Understand payment performance trends of different metrices and segmentation |  
| Insight Generation | Analyze metrics to determine most and least effective campaigns in terms of cost, reach, engagement, ad sets, ad placements, location, and keyword selection | Derive insights into campaign efficiency to guide optimization |
| Segmentation Clustering with K-Prototypes | Create segmentation from categorical and numerical variables for better segment accuracy | Identify common customer segments by their silimarity from categorical (identity) and numerical aspect |
| XGBoost Machine Learning | Perform XGBoost model with optune hyperparameter tuning to optain high accuracy and performance model | Develop a high performing churn prediction model with feature importance analysis |
| SHAPLEY Value | Apply SHAPLEY Value as advanced feature interpretation to show contribution of probability in/decreasement | To gain more insight  about each features that highly impacted probability churn |
| Segment Matrix with Value at Risk | Perform matrix visualization for each high risk segment on late payment and churn probability with estimated loss of value using VaR  | As evaluation and mitigation strategy for each segmentation, so product team can treat different strategy for different segments |
| Survival Analysis | Perform survival analysis to show how long days required until one customer decide to churn or late on their payment  | As evaluation and mitigation strategy for product team reducing high late of payment and churned customers |
| Recommendation | Provide data-driven recommendations to optimize payment performance with churned customers | Improve payment performance and reducing churn rate |
---

## Result - Slide Deck
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQWjB-EEmckqWnBU2Ys5MTjPmx4LQyhP5UE9-iyHEAlJQ4dPDmW1_jaJ3hTVx6nmVvB-bhJRYjGLLVy/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="491" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

From our analysis journey, I already found some interesting informations:
1. High and increasing late and grace payments - >62% of payments made late
2. Productive males more likely to pay in grace while females pay late
3. Millennials and Gen X comprise 82% of customers and see more delays
4. Married customers have better payment compliance
5. Higher level roles delay payments, junior roles pay late
6. Virtual accounts and credit cards preferred but see more delays
7. Increasing grace period trends across segments
8. Emerging segment has no late payments but unstable grace periods
9. Most installments not paid on scheduled due dates
10. 15.2% churn rate with 96% churning after only 1 transaction
---

### Attachments

<a href="https://colab.research.google.com/drive/1KhfEu-Z3a6ji2NvTovcW3kmMfWnonSxi?usp=sharing">>> Google Colab Link <<</a>

---

I'm grateful you took the time to explore my portfolio site and view my work. Your interest means a lot. 

Feel free to provide any feedback or ask questions - I welcome your thoughts. Thank you again for checking out my projects and considering my skills. I appreciate you taking the time to do so.

<a href="https://www.linkedin.com/in/muhammad-shalhan-assalam-b42973200/" target="_blank">>> Let's get in touch on LinkedIn! <<</a>