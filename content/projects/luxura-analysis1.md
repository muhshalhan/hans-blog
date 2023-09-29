---
title: "Luxura Analysis Part 1"
date: 2023-09-23
draft: false
author: "Muhammad Shalhan Assalam"
tags:
    - Statistic Descriptive
    - EDA
    - Hypothesis Test
    - Analysis
    - Python
    - E-Commerce
image: /images/luxura-analysis1/main.jpg
description: ""
toc:
---

## Situation
In this project, I'm part of Luxura's Data Analytics team. As fashion e-commerce company, Luxura selling several luxury fashion brands. In order to expand business partnership, Luxura needed to <b> decide which brand to prioritize as their main brand partnership </b> based on historical performance.

### Backround
Luxura is an e-commerce company that exclusively sells high-end fashion brands including <u> Adibi, Balena, and Celinna </u>. These brands have seen increasing market share over the past 3 years and rely on Luxura as their sole retail partner.

However, the brands are competitive with each other in terms of pricing and product types. Luxura needs to <b> decide which brand to prioritize in their marketing efforts in order to optimize partnership revenue </b>. Although Adibi paid the highest partnership fee, the Head of Data believes <u> historical purchase performance data should be inform the right decision </u>. By analyzing past purchase behavior across brands, user demographics, and income segments, Luxura can determine which brand has the strongest customer traction and upside potential to focus their marketing on.

### Problem Definition
The problem was that <b> <u> Luxura needed to determine which brand to prioritize marketing for,  based on the historical performance data.</b> </u>.

### Objective
In this part, the objective of this analysis:
1. State the main business problem faced by Luxura and how can we utilize Luxura's available data to answer the main problem with determined statistical analysis
2. Apply data cleaning process, including removing duplicates, correcting data type, and outliers
3. Perform descriptive statistics to see how well Luxura's data distributions
4. Provide more insight by using EDA (exploratory data analysis), especially for customer behavior
5. Perform segmentation analysis by K-Means for more insight gathering
6. Perform t-test to validate which brand has significantly greater sales performance

## Task & Action

| Task | Action | Reason |
|-|-|-|
| Identify core problem | Summarized key limitations and decisions faced by Luxura | Outlined the business context |
| Define metrics | Identified metrics like product value purchased to compare brands | Metrics focused analysis on key data points |
| Data Cleaning | Drop any missing value (<3% from total data), duplicated data, and fix missmatch data type | Make sure the data already cleaned before doing EDA |
| Exploratory data analysis | Analyzed purchase data including product value (comparing brand performance), user demographics (marital status, income level, etc), and purchasing power each segments | Provided baseline understanding of data contents |
| Remove outliers | Find IQR and apply EDA via box-plot, so we can remove outliers | Some times, outliers can be "silent killer" to our statistical models (we delete outliers as we want to take generalization/summarizing characters in all sample. Outliers can extremely leverage the value of sample ) | 
| Segmentation Analysis | Apply elbow-method or silhoutte analysis to find most fit number of segmentation, then apply K-means | K-means is used to divide Luxura's customer into several segments | 
| Test Hypothesis | In order to validate which brand is more have higher monetary value, we will apply t-test 2 tailed with 5% significance | t-test are most simple method to validate which of Adibi, Balena, or Celinna are more worth to make partner with Luxura |
| Make recommendations | Recommended which brand to prioritize based on analyzed purchase insights | Data-backed recommendations helping management to set right decision making |

---

## Result - Slide Deck

By completing this project's, I've gained crucial hands-on experience to solve main problem based on business understanding, started from data cleaning, statistical analysis, EDA, segmentation, and A/B test as well. I've enhanced my skills from those activity, that very crucial in the field of data analytics.

Based on my analysis, I've found that:
1. Adibi, Celinna, and Balena relatively has same order contribution at 33%, but Balena very depend on promotional usage rather than Celinna as luxury product (favorite by higher income) and Adibi as mass product (favorite by medium-lower income).
2. More higher income and more married customer, they tend to spend more on Celinna rather than Balenna or Adibi.
3. Buying capacity rises with higher segment class, but Balenna tend to more stable all across segment class.
4. Final t-test shows that Celinna has significantly greater sales performance compared to Balenna or Adibi.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRR6IidYed9_HdZ7vHG5foLaftIsuODU7yCzKPGjz2dtsUD2aldlS7aT6ujRTuJtQ59nScFmwbJMUO-/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="491" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

---

### Attachments

<a href="https://docs.google.com/spreadsheets/d/1Q5Vvt8-Eha1FDluX9TdtI-HpDzPA4vmW/edit?usp=sharing&ouid=113457939531194487813&rtpof=true&sd=true" target="_blank">>> Dataset Link <<</a> | <a href="https://docs.google.com/spreadsheets/d/1VgPuiz8-uhFT2Qo6BE4w_aM80n-w46klKxks9lwvkaU/edit?usp=sharing" target="_blank">>> Spreadsheet Link <<</a> | <a href="https://colab.research.google.com/drive/1GEXmGJ8yH9JV9H_cEBgGXdnCY9uK1u4K?usp=sharing" target="_blank">>> Google Colab Link <<</a>

---

I'm grateful you took the time to explore my portfolio site and view my work. Your interest means a lot. 

Feel free to provide any feedback or ask questions - I welcome your thoughts. Thank you again for checking out my projects and considering my skills. I appreciate you taking the time to do so.

<a href="https://www.linkedin.com/in/muhammad-shalhan-assalam-b42973200/" target="_blank">>> Let's get in touch on LinkedIn! <<</a>