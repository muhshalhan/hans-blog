---
title: "Zurich Marketing Campaign Analysis"
date: 2024-01-04
draft: false
author: "Muhammad Shalhan Assalam"
tags:
    - Marketing
    - Ad Campaign
    - Analysis
    - PCA
    - Benefit & Cost
    - Insurance
image: /images/zurich-marketing-campaign-analysis/main.jpg
description: ""
toc:
---

## Situation

This is my project during my internship at Zurich Insurance. In this project, Zurich's marketing team wanted to introduce their new insurance product, Zurich Ziaga Life Felaxy (Zuruch ZLF). During the 5-month campaign, the marketing team had launched 17 ad campaigns with a total ad spend of around Rp149.5 million. They have successfully converted 1890 sign-ups with 127 customers into ZLF Products. 

The marketing team believed that the campaigns were running well, but as marketing spend increased over time with bottleneck issues at sign-up convertion, they needed the help of a Data Analyst to determine which campaigns were most cost-effective and performing well over the past 5 months.

> DISCLAIMER: The data provided is a representation of the original data which amount have been adjusted.

### Backround

Zurich is a leading insurance provider serving its customers in both local and global markets. Currently, Zurich is developing their new product called Ziaga Life Flexy (ZLF). ZLF is a life insurance product that provides lifelong protection. During the coverage period, the designated family members as Beneficiaries will receive the sum insured in the event of the insured's death.

Zurich introducing their Ziaga Life Flexy as insurance product that provides lifetime protection (or up to 99 years). Within the protection period, the family designated as beneficiaries (heirs) can get up to Rp3 billion if you experience the risk of death. The cost of insurance (premium) is affordable starting from Rp20 thousand per month. In this case, you act as a Policyholder (insurance buyer), Insured (insured person), and Premium Payer (person who pays the insurance fee).


### Problem Definition

How to identify the most cost-effective ad campaigns over past 5 months in order to balance ad spend with lead generation and conversion rates?

### Objective

The objective of this project was <b> to identify the most cost-effective and well-performed ads in the last 5 months </b>. The goal was to <u> generate data-driven recommendation </u> to <b> improve conversion performance for sign-ups and purchases with marketing cost balance</b>.

## Task & Action
| Task | Action | Reason |
|-|-|-|
| Data Cleaning | Check for missing values, duplicates, outliers, inconsistencies, and formatting issues in the data | Cleaning the data is an essential first step before analysis to ensure data quality and accuracy of insights |
| EDA/EDV with Tableau | Visualize campaign metrics like cost, impressions, clicks, CTR, signups, conversions over time | Understand performance trends of different campaigns to identify high and low performers |  
| Insight Generation | Analyze metrics to determine most and least effective campaigns in terms of cost, reach, engagement, ad sets, ad placements, location, and keyword selection | Derive insights into campaign efficiency to guide optimization |
| Word Cloud for Interesting Campaign Keywords | Create word clouds from campaign name and ad content keywords | Identify common themes and keywords that may attract more traction for CTR and Signup |
| PCA Indexing for Campaign Ranking | Use PCA to rank campaigns based on multiple metrics (Funnel Size, Conversion, Benefit, and Cost) | Develop an index to objectively compare and benchmark campaign performance |
| Benefit Cost Analysis | Calculate benefit-cost ratio for each campaign based on conversions and cost | Quantify return on investment to guide budget allocation decisions |
| Campaign Matrix | Plot campaigns on matrix comparing signup/purchase rate vs net return, ad spend, and frequency  | Classify campaigns into categories by tratment quadrant to identfy most performing and least beneficial campaigns |
| Recommendation | Provide data-driven recommendations to optimize budget across top performing campaigns | Improve marketing efficiency and return on ad spend based on insights |
---

## Result - Slide Deck
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRjIcFn_Afm0KCDHlh-HmdZfgV3PkDLD6HU6rXD4J72SL-B8PgfKqSRMkddNO0QR5KAqkVQ0xMxk7D9/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="491" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

From our analysis journey, I already found some interesting informations:
1. Longer ad campaign durations (over 1.5 months) tend to perform better, indicating the importance of sustaining campaigns.
2. Video ads with compelling narratives are effective in generating signups and conversions.
3. Timing strategies should prioritize weekend attention and weekday conversions.
4. Customer list targeting consistently delivers the best results, while broader and saved audience targeting are also valuable.
5. Shifting focus from Gen Z and Boomers to Millennials and Gen X has resulted in higher awareness and performance.
6. Both genders prefer the same top three ads, with females converting better and males showing higher signup percentages.
7. Regional ad preferences has same pattern at top 3-4 ads, but the others are determined by cultural preferences, community backround, and socio-demography conditions. Such as  Java, Sumatra, and Sunda Kecil regions are more developed to adapt contemporary and viral key message rather than Kalimantan, Sulawesi, and Indonesia Timur.
8. Top ads by performance and cost-effective (can be continued):
    - Asuransi Jiwa Seharga Kopi
    - Ada Apa Ini?
9. Top ads but have bottleneck problem at signup conversion (need improvement before continue):
    - Beli Asuransi Jiwa 25K
    - 20K Dapat Apa?
    - Self-Reward
---

### Attachments

<a href="https://colab.research.google.com/drive/1L1ZPlstRJo8HUDfc7J73Wn1qih_ZYaxh?usp=sharing" target="_blank">>> Google Colab Link <<</a>

---

I'm grateful you took the time to explore my portfolio site and view my work. Your interest means a lot. 

Feel free to provide any feedback or ask questions - I welcome your thoughts. Thank you again for checking out my projects and considering my skills. I appreciate you taking the time to do so.

<a href="https://www.linkedin.com/in/muhammad-shalhan-assalam-b42973200/" target="_blank">>> Let's get in touch on LinkedIn! <<</a>