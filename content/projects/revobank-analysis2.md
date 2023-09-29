---
title: "RevoBank Fintech Analysis | Part 2: Segmentation"
date: 2023-09-24
draft: false
author: "Muhammad Shalhan Assalam"
tags:
    - Analysis
    - Segmentation
    - K-Means
    - RFM
    - Python
    - Fintech
image: /images/revobank-analysis/main.jpg
description: ""
toc:
---

## Situation
This the second part of RevoBank analysis, focused on segmentation analysis using RFM and K-means.

As a Data Analyst on RevoBank's Card Partnerships team, I was tasked with evaluating and optimizing a 6-month promotional rewards program with RevoShop to increase credit card usage and revenue while reducing program costs. My role was to analyze customer data to provide insights into behaviors that could inform strategies for customizing the rewards by segment to boost engagement in a more cost-effective manner. The goal was to leverage data-driven insights to tailor the program to customer preferences based on their customer segmentation analysis.

### Backround
RevoBank implemented an exclusive promotion for its credit card customers in partnership with RevoShop, an ecommerce marketplace. This promotion rewards cardholders with points for shopping at RevoShop to incentivize spending.

After running this promotion for 6 months, RevoBank wants to optimize the program. While it's driving card usage and merchant revenue, the promotion comes at a high cost to the bank. RevoBank needs data-driven insights into customer spending behaviors to identify ways to refine the program for maximum return.

By analyzing historical customer transaction and demographic data, I can segment users and uncover differences in behaviors and promo sensitivity. These insights can inform strategies to customize the rewards by user group to boost engagement in a more cost-effective manner. My analysis will provide the business intelligence needed to increase card usage and revenue from the partnership while reducing the bank's promotion expenses.

### Problem Definition
The problem was that RevoBank seeking a data-driven understanding of customer behaviors based on their segments to strategically tailor the RevoShop rewards program for maximum return.

### Objective
The objectives of this analysis were to:

1. Apply scaling data (robust scaling) to handling outlier problem
2. Apply RFM analysis to group customers based on recency, frequency and monetary value
3. Leverage k-means clustering to further segment users into distinct clusters
4. Identify key metrics like sales, transactions, revenue, and promo sensitivity for each cluster
5. Evaluate clusters to uncover segments aligned to program optimization goals

## Task & Action
| Task | Action | Reason |
|-|-|-|
| Data Scaling | Apply robust scaling to adjust outliers effect on RFM & K-means model | Adjusting outlier effect is very important step before we continue to segment the data |
| RFM analysis | Created RFM segments using recency, frequency and monetary value columns | Grouped customers based on key behavioral metrics |  
| K-means clustering | Applied k-means to further divide customers into granular clusters | Formed distinct segments with k-means algorithm |
| Evaluate clusters | Calculated metrics like sales, transactions, revenue, promo sensitivity for each cluster | Identified high-opportunity segments aligned to goals |
| Choose clusters | Used elbow method, silhouette analysis to select optimal number of clusters | Ensured appropriate clustering for the analysis | 
| Recommend segments | Recommended clusters with high revenue and low promo cost to target | Informed strategies to refine promotional targeting |

## Result - Slide Deck

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ1KUVUdRk-XJR6ooaVw3PerF_XJE-3nYSUzYYWTFPjymOnSGRy1BLGi3lbK7OTZWBAZbJ5q35mEZBH/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="490" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

---

### Attachments

<a href="https://drive.google.com/file/d/1bwpWSicFoFt1huv2QBIgdKLxVlLelaqJ/view?usp=drive_link" target="_blank">>> Dataset Link <<</a> | <a href="https://docs.google.com/spreadsheets/d/1XjQ1lTtFOMRSr_EisXxnM6EJYu2Y0_zt/edit?usp=sharing&ouid=113457939531194487813&rtpof=true&sd=true" target="_blank">>> Data Dictionary Link <<</a> | <a href="https://colab.research.google.com/drive/1TeJJ0HOznBSrNT1Eg_WuSGruDohirvrh?usp=sharing" target="_blank">>> Colab Link <<</a>

---

I'm grateful you took the time to explore my portfolio site and view my work. Your interest means a lot. 

Feel free to provide any feedback or ask questions - I welcome your thoughts. Thank you again for checking out my projects and considering my skills. I appreciate you taking the time to do so.

<a href="https://www.linkedin.com/in/muhammad-shalhan-assalam-b42973200/" target="_blank">>> Let's get in touch on LinkedIn! <<</a>