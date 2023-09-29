---
title: "IBM HR Analytics"
date: 2023-09-22
draft: false
author: "Muhammad Shalhan Assalam"
tags:
    - DARCI
    - SMART
    - RCA
    - Hypothesis Test
    - Analysis
    - HR Analytics
image: /images/ibm-hr-analysis/main.jpg
description: ""
toc:
---

## Situation

This project was conducted during my role as a Data Analyst student at RevoU. In this project, we use IBM as organization that experiencing <b> a high annual attrition rate of 15% </b>, leading to many vacant positions. 

> DISCLAIMER: This project is focused on exploring the basic concepts of business case understanding. The data cleaning, EDA, and GBM modelling processes are not shown directly in the slide deck. You can access google colab to see how it works (at the end).

### Backround

IBM is a large <b> technology company </b> with over 4000 employees. Over the <u>past few years, they have experienced <b> rising attrition </b> </u>, with their annual attrition rate <b> climbing to 15% </b> - significantly higher than industry averages.

This high turnover has created numerous challenges for IBM. They have <u> struggled to fill open roles in a timely manner, delaying critical projects </u>. The costs of recruiting, onboarding and training new hires to replace departing staff has also strained budgets.

To address this issue, IBM HR department along with data team, determined a <b> data-driven approach </b> was needed to gain insights into why employees were leaving. By <u> analyzing patterns in attrition </u>, they aimed to <b> identify specific problems </b> that, if fixed, could improve retention. This would enable leadership to develop targeted strategies to reduce churn and meet their goal of lowering attrition by the following year.

### Problem Definition

The problem we needed to solve was identifying the main drivers of attrition at IBM in order to recommend data-driven strategies to reduce the attrition rate.

### Objective

The objective of this project was <b> to analyze HR data to uncover insights about which factors most strongly correlate with employee attrition at IBM </b>. The goal was to <u> identify actionable solutions </u> to <b> improve retention and reduce the attrition rate by 8% for the following year </b>.

## Task & Action
| Task | Action | Reason | 
|-|-|-|  
| Determines Stakeholders | Apply DARCI Framework | DARCI (Directed, Accountable, Responsible, Consulted, Informed) framework is one of the most comprehensive stakeholder identification framework, most universally aplicated in various industries |
| State the Main Problem | Apply SMART Problem Statements | SMART (Specific, Measurable, Achievable, Relevant, and Time-bound) is one of best method to clearly assign main goal of a project, based on their conditions, metrics, and deadlines |
| Make Flow Analysis | Apply Root Cause Analysis | Root Cause are very helpfull to identify "suspect" of the main cause, divided by main problem, sub-problem, and root of each problems. |
| Collect and clean HR data | Check wheter data already clean and availibility each variable that will used as metrics in this project | This provided the necessary data to analyze drivers of attrition |
| Perform exploratory data analysis | Analyzed distributions and relationships in the data to identify patterns and surface potential factors related to attrition | Helped uncover insights about potential cause of attrition. This is also help us to validate the root cause analysis |
| Make Initial Hypothesis | Construct hypothesis based on priritized factor given from RCA, determine the relevant metrics to test this hypothesis | Hypothesis is scientific procedure that obligatory for validating our insight and RCA |
| Build gradient boosting model | Developed a GBM model to identify the strongest predictors of employee attrition based on the IBM HR data | The results would reveal the highest priority issues driving attrition at XYZ Ltd |
| Identify top factors driving attrition based on feature importance | Used GBM model results to determine the factors most strongly correlated with employee churn, like satisfaction, work-life balance, career growth | These key drivers would need to be addressed to improve retention |  
| Validate the Hypothesis | Validate each prioritized hypothesis with their metrics based on result from EDA and GBM model | This is will help us to validate main cause of high attrition rate at IBM. |
| Make recommendations | Provide strategic recommendation for HR team based on main findings through monitoring via metrics | Targeted, data-backed recommendations can help maximize impact of retention efforts |

---

## Result - Slide Deck

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTjsq1ov4omx3quW3XYDdLdhOs58QtMpmga4PdWrosgFLceXAYU86k4c-CiCfXdumfWYWVyYXd0RimR/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="491" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

---

### Attachments

<a href="https://drive.google.com/drive/folders/1UpuPkCT5ibkuGT_wCEcR5DS5QKftBP9C?usp%3Dsharing&sa=D&source=editors&ust=1695395102213732&usg=AOvVaw2eLVDK_77m22X6OTJmiCrt" target="_blank">>> Dataset Link <<</a> | <a href="https://docs.google.com/spreadsheets/d/1FMganV-GKBQccBHdAZzN9HcU7tdST44t/edit?usp%3Dsharing%26ouid%3D113457939531194487813%26rtpof%3Dtrue%26sd%3Dtrue&sa=D&source=editors&ust=1695395102215944&usg=AOvVaw3X5j_6SM3Xh4OJjnFIPW0Q" target="_blank">>> Data Dictionary Link <<</a> | <a href="https://colab.research.google.com/drive/1RJpn2i35BzO7-uXEaCRUwBUa3K8PgY2a?usp%3Dsharing&sa=D&source=editors&ust=1695395303205145&usg=AOvVaw1oGZx0yJ289pTTtKSWCuoz" target="_blank">>> Google Colab Link <<</a>

---

I'm grateful you took the time to explore my portfolio site and view my work. Your interest means a lot. 

Feel free to provide any feedback or ask questions - I welcome your thoughts. Thank you again for checking out my projects and considering my skills. I appreciate you taking the time to do so.

<a href="https://www.linkedin.com/in/muhammad-shalhan-assalam-b42973200/" target="_blank">>> Let's get in touch on LinkedIn! <<</a>